# tutorial_git

GHost

    - Cleaning the House

        git checkout -b {nueva_rama}
        git add *
        git commit -m 'Nuevo cambio'
        git push --set-upstream {nueva_rama}

        git checkout master
        git branch -D {nueva_rama}
        git push origin --delete {nueva_rama}