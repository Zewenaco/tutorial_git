# tutorial_git

GHost

    Github workflow

        git checkout -b {nueva_rama}
        git add *
        git commit -m 'Nuevos cambios'
        git push --set-upstream origin {nueva_rama}
        ... Pull Request ...
            comments
                more comments
        git add *
        git commit -m 'Sugerencias en PR'
        git push
        ...
        ...
        git checkout develop
        git merge --no-ff {nueva_rama}
        git push