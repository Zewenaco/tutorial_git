# tutorial_git

GHost

    - Fast Forward Merge ( Linear Merge )

        git checkout -b {nueva_rama}
        git add *
        git commit -m 'Nuevos cambios'
        git push --set-upstream origin {nueva_rama}

        git checkout -b {nueva_rama_2}
        git add *
        git commit -m 'Nuevos cambios'
        git add *
        git commit -m 'Nuevos cambios'
        git push --set-upstream origin {nueva_rama_2}

        git rebase -i HEAD~2
        git push -f

        git checkout {nueva_rama}
        git merge --no-ff {nueva_rama_2}
        git push