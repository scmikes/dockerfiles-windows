FROM node:8.11.1-windowsservercore

RUN npm install --global windows-build-tools ; \
    $env:PATH += ';{0}\.windows-build-tools\python27' -f $env:USERPROFILE ; \
    [Environment]::SetEnvironmentVariable('PATH', $env:PATH, [EnvironmentVariableTarget]::Machine)
