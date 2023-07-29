// my 1st script 
pipeline {
	agent {
		label {
			label "built-in"
			customWorkspace "/mnt/takte"
			}
		}
		stages {
			stage ('stage-1') {
				steps {
						sh "cp -r index /var/www/html"
						sh "chmod -R 777 /var/www/html"
					}
				}
			}
}			
				
					
