pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'echo off'
                bat 'set path="D:\Program Files (x86)\Graphviz2.38\bin\;%path%;" '
                bat 'REM set out1=%1                                           '
                bat 'REM set file2=%2                                          '
                bat 'set /p out1="pls give a name to save>>:>"                 '
                bat '"cookies.sqlite"                                          '
                bat 'set /p file2="pls give the sqlite file>>:>"               '
                bat '"D:\Tor Browser\Browser\TorBrowser\Data\Browser\profile.default\cookies.sqlite"'
                bat 'set sql3="D:\Program Files (x86)\Graphviz2.38\node_modules\sqleton\bin\sqleton"'
                bat 'shift'
                bat 'node %sql3% -o %out1% %file2%'
                bat 'echo "out file is" %out1%'
                bat 'echo "file is" %file2%'
            }
        }
    }
}

