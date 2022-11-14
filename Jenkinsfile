pipeline {
          agent {
		      label {
			    label '172.31.39.222'
			  }
			}  
			    stages {
				     stage ('noad-1') {
					       steps {
						       
							   sh "sudo yum install httpd -y"
							   sh "service httpd start"
							   sh "cp -r index.html /var/www/html/"
							   sh "chmod -R 777 /var/www/html/index.html"
					 }
				
				}

            }

}
