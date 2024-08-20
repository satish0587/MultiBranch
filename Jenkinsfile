pipeline
  {
   agent any
   stages
   {
   stage("checkout source code")
   {
     steps
     {
      git branch: 'feature3', url: 'https://github.com/satish0587/MultiBranch.git'
     }
    }
   stage("checkforakeyword")
   {
    steps
    {
     sh 'cat contact.html | grep -i wealth'
    }
   }
  }
}
