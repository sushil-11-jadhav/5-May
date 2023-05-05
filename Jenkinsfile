pipeline {
agent {
	label {
		lable "slave"
		customWorkspace "/mnt/doct"
		
	}
	}
		stages {
			stage ("stage1") {
		
				steps {
						sh "yum install httpd -y"
						sh "service httpd start"
					        sh "cp /mnt/doct/index.html /var/www/html"
						sh "chmod -R 777 /var/www/html/index.html"
				}
			
			}
		
		}


}
