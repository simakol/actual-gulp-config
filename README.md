# actual-gulp-config
Here you can find actual configuration for a gulp project. 

# Run in dev mode
```
npm run dev
```
# Build
```
npm run build
```
# Get zip of build
```
npm run zip
```
# Deploy project on FTP server
1. Fill configFTP object with your data.(src/gulp/config/ftp.js)
2. Set up your directory name in field path of path object src/gulp/config/path.js
3. Run
```
npm run deploy
```

