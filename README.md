# git_pull_push
Shell function to made easy source code to pull from or push to git

# Instructions
Configuration Structure
parents_folder :

    development :
        |- your_project1
        |- your_project2
        |- git_pull_push

Clone git_pull_push :  To your development parents folder

    git clone -b master https://github.com/uzzal2k5/git_pull_push.git


Add  your repository name in pull_push.conf, each repository on each line
 the run 'github_source'

    cd  git_pull_push

    # Add your repository name in pull_push.conf, each repository on each line
    vi config/pull_push.conf

    example_repository1
    example_repository2
     .
     .
    example_repositoryN



To push or pull from your git run github_source

    sh github_source
