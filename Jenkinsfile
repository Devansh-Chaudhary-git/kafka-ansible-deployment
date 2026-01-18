@Library('Kafka-shared-lib') _

node {
    script {
        def yamlText = libraryResource('kafka-config.yaml')
        def config   = readYaml(text: yamlText)

        config.REPO_URL = 'https://github.com/Devansh-Chaudhary-git/kafka-ansible-deployment.git'
        config.BRANCH   = 'main'

        kafkaAnsiblePipeline(config)
    }
}

