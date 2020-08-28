# upload tool

a really simple upload/download tool for windows-cmd and a really simple upload tool for linux-bash

In the Windows folder there is also a download.bat file because in contrast to linux, as far as I know, no download tool is preinstalled

## Usage:

### Linux:

#### Upload:

```
upload [path to file] [filename]
```

#### Download:

```
sudo wget [URL to file]
```

### Windows:

#### Upload:

```
upload [path to file] [filename]
```

#### Download:

```
download [URL to file] [filename to save as]
```

## Linux setup:

```
sudo wget https://github.com/kordexjan/upload-tool-Linux/archive/master.zip -P /bin/
```

```
sudo unzip /bin/master.zip
```

```
sudo cp /bin/upload-tool-Linux-master/upload /bin/
```

```
sudo chmod +x /bin/upload
```

## Windows setup:

Download the [zip file](https://github.com/kordexjan/upload-tool-windows/archive/master.zip)

Move the upload.bat and download.bat into C:\Windows\system32
