# Mysys2
Minimal windows distro CLI based on unix
Despite its Unix-like nature, MSYS2's commands closely mirror those found in Linux systems because it aims to offer a similar user experience.

Here is a revised list of MSYS2 commands tailored to its Windows environment, emphasizing commands commonly used within MSYS2:

### **MSYS2 CLI Commands**

#### **1. File and Directory Management**

- **List files and directories:**
  ```bash
  ls
  ```

- **Change directory:**
  ```bash
  cd directoryname
  ```

- **Create a new directory:**
  ```bash
  mkdir directoryname
  ```

- **Remove a directory:**
  ```bash
  rmdir directoryname
  ```

- **Remove a file:**
  ```bash
  rm filename
  ```

- **Copy files:**
  ```bash
  cp sourcefile destinationfile
  ```

- **Move files:**
  ```bash
  mv sourcefile destinationfile
  ```

- **Find files:**
  ```bash
  find /path/to/search -name filename
  ```

#### **2. File Viewing and Editing**

- **Display file contents:**
  ```bash
  cat filename
  ```

- **View file content page by page:**
  ```bash
  less filename
  ```

- **Search within files:**
  ```bash
  grep "searchtext" filename
  ```

- **Edit files:**
  ```bash
  nano filename
  ```

  or

  ```bash
  vim filename
  ```

#### **3. System Information and Management**

- **Display current working directory:**
  ```bash
  pwd
  ```

- **Show system information:**
  ```bash
  uname -a
  ```

- **Display disk usage:**
  ```bash
  df -h
  ```

- **Display memory usage:**
  ```bash
  free -m
  ```

- **Show process list:**
  ```bash
  ps aux
  ```

- **Kill a process by PID:**
  ```bash
  kill pidnumber
  ```

- **Show active network connections:**
  ```bash
  netstat -an
  ```

#### **4. Package Management**

- **Update package lists:**
  ```bash
  pacman -Syu
  ```

- **Install a package:**
  ```bash
  pacman -S packagename
  ```

- **Remove a package:**
  ```bash
  pacman -R packagename
  ```

- **Search for a package:**
  ```bash
  pacman -Ss packagename
  ```

#### **5. Networking**

- **Ping a host:**
  ```bash
  ping hostname
  ```

- **Trace route to a host:**
  ```bash
  traceroute hostname
  ```

- **Download a file from the web:**
  ```bash
  wget http://example.com/file
  ```

#### **6. File Compression**

- **Create a tarball archive:**
  ```bash
  tar -cvf archive.tar filename
  ```

- **Extract a tarball archive:**
  ```bash
  tar -xvf archive.tar
  ```

- **Create a gzipped tarball archive:**
  ```bash
  tar -czvf archive.tar.gz filename
  ```

- **Extract a gzipped tarball archive:**
  ```bash
  tar -xzvf archive.tar.gz
  ```

#### **7. Shell Scripting**

- **Execute a script:**
  ```bash
  ./scriptname.sh
  ```

- **Make a script executable:**
  ```bash
  chmod +x scriptname.sh
  ```

#### **8. Permissions**

- **Change file permissions:**
  ```bash
  chmod permissions filename
  ```

- **Change file owner:**
  ```bash
  chown owner:group filename
  ```

### **Summary**

This list reflects MSYS2's Unix-like command set adapted for Windows. It includes commands for file management, system operations, package management, networking, and more, tailored to the MSYS2 environment.
