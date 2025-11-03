pipeline {
			agent{
						label{
								label "slave-1"
								customWorkspace "/mnt/pipeline"
						
						}
			}
			
			stages {
			        stage("stage-1"){
									steps {
											sh "rm -rf *"
											sh "mkdir stage-1"
									
									}
					}
			
					stage("stage-2"){
									steps{
										dir("/mnt/pipeline-1"){
												sh"mkdir stage-2"
										
										}
				
				
				}
				
				}
							stage("stage-3"){
				    
										steps{
										   dir("/mnt/pipeline-3"){
												sh"mkdir stage-3"
										
										}
				
				
				}
				
				}			
			}
			}
