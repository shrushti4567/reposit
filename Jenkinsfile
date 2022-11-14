pipeline {
         agent {
		   label {
		        label 'built-in'
		    }
		 }
                stages {
				      stage ('stage-1') {
					          steps {
							  sh "rm -rf *"
							  sh "yum install tree -y"
							  }
						}
						       stage ('172.31.39.222') {
							                      steps {
										                     sh "rm -rf *"
												     sh "yum install httpd -y"
													 sh "cd /var/www/html"
													 echo "this is index file" >> index.html /var/www/html
													 sh "chmod 777 index.html"
													 }
												}
                                                   stage ('172.31.8.14') {
                                                            steps {
								  sh "rm -rf *"  
                                                                  sh "yum install httpd -y"
                                                                  }
                                                             }
															 
							 
                           }
						   


}
