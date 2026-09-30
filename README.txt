BUILD THE APK (no Android Studio needed)
1. Create a free account at github.com and make a new repository (any name).
2. Upload ALL the files/folders from this zip to the repository (keep the .github folder).
   If the .github folder does not upload, use Add file > Create new file, name it
   .github/workflows/build.yml and paste the contents of that file.
3. Open the repository's "Actions" tab > "Build APK" > wait about 3-5 minutes for the green tick.
4. Open the finished run, download "DontTouchTheRed-APK" (a zip), unzip it to get app-debug.apk.
5. Send app-debug.apk to your phone and install it (allow "install unknown apps" if asked).
To change the game later, replace app/src/main/assets/index.html and push again.
