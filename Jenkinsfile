pipeline {
   agent any
   stages {
      stage('Example') {
         steps {
         	// Call the getChangeset function
         	githubChangeset()
         	
            // Call the helloWorld() method and pass a value
            helloWorld("Craig")
         }
       }
   }
}
