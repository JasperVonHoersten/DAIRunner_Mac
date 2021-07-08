pipeline {
    agent any

    stages {
        stage('Start') {
            steps {
                echo 'Build starting'
            }
        }

        stage('Run Tests'){
        steps {
		echo 'Starting DAI Runner...'
            sh 'chmod +x DAIrunner'
            sh './DAIrunner -v https://demo.dai.eggplant.cloud:443/ jasper.vonhoersten@keysight.com Lunaperla372! sorting jasper.vonhoersten@keysight.com Salesforce_Fusion_Model_Jasper JasperLocal /Users/vonhoers/"OneDrive - Keysight Technologies"/"EggPlant Suites"/SalesForce/Salesforce_FusionModel.suite'
        }
        }
    }
}
}
