node {
    
   git url: "https://github.com/hotwilson/jenkins2.git"

   sh 'git rev-parse HEAD > GIT_COMMIT'
   def shortCommit = readFile('GIT_COMMIT').take(6)

   stage '1'
   echo 'branch'
}
