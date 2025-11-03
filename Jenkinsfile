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
				dir("/mnt/pipeline-1"){
										steps{
												sh"mkdir stage-2"
										
										}
				
				
				}
				
				}
							stage("stage-3"){
				dir("/mnt/pipeline-3"){
										steps{
												sh"mkdir stage-3"
										
										}
				
				
				}
				
				}			
			}
			}
