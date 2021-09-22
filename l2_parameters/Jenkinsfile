properties([parameters([choice(choices: ['master', 'feature-1', 'feature-2'], description: 'Select brunch to build', name: 'brunch')])])

node 'node1'{
    stage( 'Scm checkout ' ){
        echo "Pulling changes from the brunch ${params.brunch}"
    }
}