# tutorial_git

GHost

    Git Reset

        git checkout -b {nueva_rama}
        git add *
        git commit -m 'Nuevos cambios'
        git push --set-upstream origin {nueva_rama}
        
        ... x1
        git add *
        git commit -m
        ...

        ... x2
        git add *
        git commit -m
        ...

        ... x3
        git add *
        git commit -m
        ...

        git reset --soft HEAD~3
        git push -f