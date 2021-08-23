pipeline {
    agent any
    environment {
        branch_name = "master"
        git_url = "https://github.com/pemmasani1200/DevOpsClassCodes.git"
        SERVICE_NAME = "ecs-fargate-cluster-svc"
        IMAGE_VERSION = "${BUILD_NUMBER}"
        TASK_FAMILY = "first-run-task-definition"
        DESIRED_COUNT = "1"
        REGION = "us-east-2"
        CLUSTER_NAME = "ecs-fargate-cluster-test"
		ECR_REPO = "011194234014.dkr.ecr.us-east-2.amazonaws.com/irving"
    }

    stages {
        stage('Build') {
            steps {
		    echo "${SERVICE_NAME}"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
