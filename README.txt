Copyright © 2020 CIS Maxwell, LLC. All rights reserved.
Copyright © 2020 The Beach Institute

Build:
Install Go on your machine https://golang.org/doc/install

  On Bash:
    GOPATH="path-to-flasher-source" GOOS=[darwin|linux|windows] GOARCH=amd64 go build -o BeachOS-flasher_[darwin|linux|windows.exe]
  On Cmd:
    SET GOPATH="path-to-flasher-source"
    SET GOOS=[darwin|linux|windows]
    SET GOARCH=amd64
    go build -o BeachOS-flasher_[darwin|linux|windows.exe]
  On PowerShell:
    $Env:GOPATH="path-to-flasher-source"; $Env:GOOS = "[darwin|linux|windows]"; $Env:GOARCH = "amd64"; go build -o BeachOS-flasher_[darwin|linux|windows.exe]

Execution:
Plug each device of a same model to a USB port

The following files must be available in the current directory:
    BeachOS factory image

 On Windows:
    Double-click on BeachOS-flasher_windows.exe (will not show error output)
    or 
    Open PowerShell or Command Line
    Type: .\BeachOS-flasher_windows.exe
    Press enter
 On Linux:
    Open a terminal in the current directory
    Type: sudo ./BeachOS-flasher_linux
    Press enter
 On Mac:
    Open a terminal in the current directory
    Type: ./BeachOS-flasher_darwin
    Press enter