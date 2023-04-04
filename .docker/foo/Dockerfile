FROM mcr.microsoft.com/windows/servercore:ltsc2019
LABEL project=hello

RUN powershell Set-Culture -CultureInfo en-NZ; Set-TimeZone -Id 'New Zealand Standard Time'

CMD ["echo", "Hello"]
