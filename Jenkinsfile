node{
    stage ('SCM Checkout'){
    git 'https://github.com/KollaNarasimharao/Emailnotification_PipelineScript.git'
    }
    stage ('Email Notification'){
    mail bcc: '', body: 'This is Narasimha', cc: '', from: '', replyTo: '', subject: 'Jenkins Jobs', to: 'nanichowdary9@gmail.com'
    }
    
}
