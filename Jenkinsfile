pipeline {
  agent any
  stages
   {
         stage("GIT")
	 {
           steps
		{
		git "https://github.com/Lalit280/mar-02.git"
		}
	 }
	 stage("RUN")
         {
           steps
		{
		sh "java Demo.java"
		}
	 }
   }
}
