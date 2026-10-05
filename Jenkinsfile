pipeline{
    agent any;
    stages{
        stage("code"){
            steps {
                git url: "https://github.com/musaqim/humairakhan.git",branch: "master"
                echo "code clone bhi ho gaya........."
            }
        }
        stage("build"){
            steps{
                echo "docker build se build bhi ho gaya................."
            }
        }
        stage("test"){
            steps{
                echo "devloper test karega.................."
            }
        }
        stage("deploy"){
            steps{
                echo "deploy bhi ho gaya...................."
            }
        }
    }
}







