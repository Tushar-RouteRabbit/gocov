#!groovy

node {

	try {
    stage 'Test stage'
      sh `echo Hello`
      
	} catch (any) {
		currentBuild.result = 'FAILURE'

		throw any //rethrow exception to prevent the build from proceeding
	} finally {
		
	}

}
