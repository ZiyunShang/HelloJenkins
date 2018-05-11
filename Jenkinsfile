node('HelloJenkins'){
	def batFolder = "D:\\"

	currentBuild.result = 'SUCCESS'

	stage('Build'){
		echo "Build..."
		bat batFolder + test.bat
	}
}