## Setting up my Git Repository

1. Instructions to set up my local folder to point to Github

    ```bash
    
    echo "# colmaracademy" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git branch -M main
    git remote add origin https://github.com/thinktinker/colmaracademy.git
    git remote -v
    git push -u origin main

    ```

2. In the event that the URL repo is set wrongly, use the following command to set the correct url:

    ```bash
    
    git remote set-url origin https://github.com/thinktinker/colmaracademy.git
    git remote -v
    git push

    ```
