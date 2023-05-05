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
						yum install httpd -y
						service httpd start
						chmod -R 777 /var/www/html/index.html
				}
			
			}
		
		}


}
