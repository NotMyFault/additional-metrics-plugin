if (env.JENKINS_URL == 'https://ci.jenkins.io/') {
    buildPlugin(findbugs: [archive: true, unstableTotalAll: '0'], checkstyle: [run: true, archive: true])
} else {
    node {
        echo "hello"
    }
}
