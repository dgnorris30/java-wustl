Rework of https://github.com/nkunkee/demo_java_jersey 




	
>git clone https://github.com/dgnorris30/java-wustl.git
>
>cd java-demo
>
>PROJECT_NAME="demonstration-project"
>	
>oc new-project $PROJECT_NAME
>	
>oc process -f .openshift/openjdk18-s2i.yaml | oc create -f - -n $PROJECT_NAME
