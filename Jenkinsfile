pipeline
  {
   agent any
   stages
   {
   stage("checkout source code")
   {
     steps
     {
      git branch: 'feature2', url: 'https://github.com/satish0587/MultiBranch.git'
     }
    }
   stage("checkforakeyword")
   {
    steps
    {
     sh 'cat about.html | grep -i healthcare' 
    }
   }
  }
}
