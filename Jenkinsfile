pipeline {
  agent any
  stages {
    stage('Veracode') {
      steps {
        veracode(vid: '16f05bc7ba21341d731195248f4d8c83', vkey: '12e441a7584e278445e89c6d12d63a9b907d9e22ea6c646b563aeaeb92a2152df45d72bce84054cd02122d51a95a27aaf7f4f99f0ba9141fd84e1daa0d325958', applicationName: 'Portal Smiles - BR', waitForScan: true, criticality: 'Very High', scanName: '$buildnumber', uploadIncludesPattern: '**/**.jar, **/**.war', scanIncludesPattern: '**/**.jar, **/**.war')
      }
    }

  }
}