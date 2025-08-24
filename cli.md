# Practice Drill 1 - Directory Structure

## Commands 
- maheswaarreddy@maheswaarreddy-VivoBook-ASUSLaptop-K3502ZA:~$ 
- maheswaarreddy@maheswaarreddy-VivoBook-ASUSLaptop-K3502ZA:~$ mkdir -p hello/five/six/seven
- maheswaarreddy@maheswaarreddy-VivoBook-ASUSLaptop-K3502ZA:~$ mkdir -p hello/one/two/three/four
- maheswaarreddy@maheswaarreddy-VivoBook-ASUSLaptop-K3502ZA:~$ touch hello/five/six/c.txt
- maheswaarreddy@maheswaarreddy-VivoBook-ASUSLaptop-K3502ZA:~$ touch hello/five/six/seven/error.log
- maheswaarreddy@maheswaarreddy-VivoBook-ASUSLaptop-K3502ZA:~$ touch hello/one/a.txt hello/one/b.txt
- maheswaarreddy@maheswaarreddy-VivoBook-ASUSLaptop-K3502ZA:~$ touch hello/one/two/d.txt
- maheswaarreddy@maheswaarreddy-VivoBook-ASUSLaptop-K3502ZA:~$ touch hello/one/two/three/e.txt
- maheswaarreddy@maheswaarreddy-VivoBook-ASUSLaptop-K3502ZA:~$ touch hello/one/two/three/four/access.log

## Explanation 
- `mkdir -p` : "mkdir" creates the directory and "-p" is a flag. "-p" it creates a nested directories in one command.

- `touch` : Creates empty files if they do not exist. If the file already exists, `touch` updates its last modified. This makes it useful for both file creation and quickly updating file.


## Result 
### Final Resulting Structure
- hello
- ├── five
- │   └── six
- │       ├── c.txt
- │       └── seven
- │           └── error.log
- └── one
    - ├── a.txt
    - ├── b.txt
    - └── two
        - ├── d.txt
        - └── three
            - ├── e.txt
            - └── four
                - └── access.log