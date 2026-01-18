@Library('kafka-shared-lib') _

def config = readYaml text: libraryResource('kafka-config.yaml')

config.REPO_URL = 'https://github.com/Devansh-Chaudhary-git/kafka-ansible-deployment.git'
config.BRANCH   = 'main'

kafkaAnsiblePipeline(config)

