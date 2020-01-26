# rozhlasdl-exe
Executable for rozhlasdl project.

Known issue: In some cases, the download can file when using this binary with a similar error message:
```
File "C:\Users\user\AppData\Local\Temp\_MEI2402\FileDownloader.py", line 86, in url_download
    urlretrieve(url, path, self.progress_bar)
  File "urllib\request.py", line 257, in urlretrieve
FileNotFoundError: [Errno 2] No such file or directory: 'C:\Users\user\Downloads\vltava\\audio_file.mp3'
```
