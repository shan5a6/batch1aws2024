pipeline {
  agent any 
  stages {
    stage('working with file operations') {
      steps {
        script {
          File file = new File("/tmp/testdata.txt")
					for line in file.readLines() {
						println "your line is ${line}"
					}
					// python 
					// file = open("/tmp/testdata.txt","r")
					// for line in file.readlines():
					// 	print(line)
        }
      }
    }
  }
}
