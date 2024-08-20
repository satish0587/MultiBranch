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
   stage("check-the-sourcecode")
   {
    steps
    {
     sh 'mvn compile'
    }
   }
     stage("run-test-case")
     {
       steps
       {
         sh 'mvn test'
       }
     }
     stage("create-the-package")
     {
       steps
       {
         sh 'mvn package'
       }
     }       
  }
}
