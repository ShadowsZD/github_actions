pipeline {    agent any

    parameters {        
      choice(name: 'FILE_MOdDE', choices: ['Server', 'Git'], description: 'Mode to get file from')        string(name: 'FILE_PATH', description: 'Full file path with file extension on server (/home/user/file.xlsx) or on GIT (/files/file.xlsxgit ')        string(name: 'GIT_BRANCH', description: 'Branch on git to get file from')        string(name: 'GIT_REPOSITORY_URL', description: 'Git repository that excel file is stored on')        string(name: 'GIT_TOKEN', defaultValue: 'globalVars.GIT_TOKEN', description: 'Git token to access repository')    }

    stages {        stage('Check Parameters'){            steps{                script{                 (a,b) = ['b', 'a']                   echo "a: ${a}"                   echo "b: ${b}"                }            }        }    }
