# Dockerfile
FROM mcr.microsoft.com/powershell:latest

# Set the working directory in the container
WORKDIR /app

# Copy the PowerShell script into the container
COPY FilesSorter.ps1 .

# Set the entry point to run the PowerShell script
ENTRYPOINT ["pwsh", "-File", "./FilesSorter.ps1"]
