# Use a base image that has PowerShell
FROM mcr.microsoft.com/powershell:latest

# Set the working directory
WORKDIR /app

# Copy the PowerShell script into the container
COPY FilesSorter.ps1 .

# Set the entrypoint to PowerShell
ENTRYPOINT ["pwsh", "./FilesSorter.ps1"]
