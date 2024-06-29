# Server

- Files must be in at least one folder, to indicate album
  - Even if the album tag is supplied, it doesn't work correctly
  - Must be in a folder with the album name
- Artists are split using `/` or `;`

## How to make

- Backend Flask server
- Frontend Svelte or Vue server
  - Makes requests to backend server for downloading, searching
  - Makes requests to Jellyfin for playlist modification, searching

### Backend

- Flask
- Uses `yt-dlp` for downloading
- Not sure what to use for searching

### Flow

- User inputs search or URL into frontend
  - If URL, skip next 4 steps
- Frontend sends request to backend to search for given string
- Backend responds with search result(s)
- Frontend displays results
- User picks result, frontend sends URL of result to backend
- Backend downloads URL
- Backend sends frontend file and tag data
- Frontend displays data and file preview
- User makes changes as necesarry
- Frontend sends updated data to backend
- Backend saves file with new data
- Backend sorts file into correct location

### Updated Flow

- Frontend gives backend url to download
- Backend downloads file and gives frontend filepath and metadata

## Music Management

### General Music Management

- Can see nice list of artists -> albums -> songs
- Easily search youtube/soundcloud/bandcamp

### Music Playlist Management

- Can see nice list of playlists -> songs
- Easily search server
- Select multiple and remove from playlist or add to another playlist

## Video Management

### General Video Management

- Can see nice list of channels -> videos
- Easily search youtube

### Video Playlist Management

- Can see nice list of playlists -> videos
- Easily search server
