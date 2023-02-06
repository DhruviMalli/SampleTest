pipeline
 {
    agent any

    stages 
    {
        stage('Build') 
        {
            steps 
            {
                echo 'Build App'
            }
        }
        stage('Test') 
        {
            steps 
            {
                echo 'Test App'
            }
        }
        stage('Deploy') 
        {
            steps 
            {
                echo 'Deploy Application'
            }
        }
    }
        post
        {
            always
            {
                emailext body: 'Summary', subject: 'Pipeline Status', to: 'marrymejungkook0197@gmail.com'
            }
        }
    }
