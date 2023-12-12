pipeline {
Agent any
stages{
stage('check validate') {
steps {
Echo 'i am validating the code'
}
}
stage('compaling the code') 
}
}
stage('install') {
steps {
Echo'i am installing the code'
}
}
stage('deploy')
{
steps {
Echo'i am deploying the code'
}
}
}
}
