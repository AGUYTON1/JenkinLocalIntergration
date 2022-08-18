pipeline{
    agent any
    stages{
        stage("test1"){
        steps{
            echo "trying to get this"
        }
        }
        stage("test2"){
        steps{
            echo "I need practice"
        }    
        }
        stage("test3"){
        steps{
            mail bcc: '', body: 'DId it work', cc: '', from: '', replyTo: '', subject: 'Jenkins Test Email', to: 'aguyton01@gmail.com,shanesehogg@gmail.com'
        }    
        }
    }
}
    
