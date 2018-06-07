pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'echo off'
                bat 'set path="D:/Program Files (x86)/Graphviz2.38/bin/;%path%;" '
                bat 'set out1="cookiessqleton"                 '
                bat 'set file2="D:/Tor Browser/Browser/TorBrowser/Data/Browser/profile.default/cookies.sqlite"'
                bat 'set sql3="D:/Program Files (x86)/Graphviz2.38/node_modules/sqleton/bin/sqleton"'
                bat 'echo "\%sql3\%" "is sql3 path"'
                bat 'shift'
                bat 'node %sql3% -o %out1% %file2%'
                bat 'echo "sql3 path is" %sql3%'
                bat 'echo "out file is" %out1%'
                bat 'echo "file is" %file2%'
            }
        }
    }
}

