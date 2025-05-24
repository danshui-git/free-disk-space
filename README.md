# free-disk-space

````
    - name: 释放Ubuntu磁盘空间
      uses: 281677160/free-disk-space@main
      with:
        remove_android: true
        remove_dotnet: true
        remove_haskell: true
        remove_tool_cache: true
        remove_swap: true
        remove-docker: true
        remove_packages: "azure-cli google-cloud-cli microsoft-edge-stable google-chrome-stable firefox postgresql* temurin-* *llvm* mysql* dotnet-sdk-*"
        remove_packages_one_command: true
        remove_folders: "/usr/share/swift /usr/share/miniconda /usr/share/az* /usr/share/glade* /usr/local/lib/node_modules /usr/local/share/chromium /usr/local/share/powershell"
        testing: false
````
