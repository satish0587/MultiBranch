pipeline
  {
   agent any
   stages
   {
   stage("checkout source code")
   {
     steps
     {
      git branch: 'feature1', url: 'https://github.com/satish0587/MultiBranch.git'
     }
    }
   stage("checkforakeyword")
   {
    steps
    {
     sh 'cat index.html | grep -i healthcare' 
    }
   }
  }
}
