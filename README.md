# DevOps-Project
DevOps learning and practices
https://github.com/yankils/Simple-DevOps-Project
https://wipro.udemy.com/course/valaxy-devops/learn/lecture/15899612#overview

HW details:
Minimum Hw required to install devops tools
Tools installation:
in VM/cloud

Development process. [DevOps]
Application architecture. [Micro services]
Deployment & Packaging [continarization]
Application infrastucre. [cloud]

paln,code,create,test,release,deploy,operate
Agile delivery[plan,build,test], agile ops[deploy,monitor logs,support]
plan,develop,build,test,deploy,relaes,monitor

Linux
file types
file creation
file permissions
file operations
processes. PS
search patterns. grep/egrep
replace strings sed
display the lines from a file head,tail,awk
network commands
hosta
ipconfig.
links between files soft and hard link

Tools classification:
Collaberatiob:
Application lifecycle management
communication & chat Options
Knowledge sharing
Build:
SCM/VCS:git,bitbucket
CI:jenkins,bamboo
Build:Maven,Docker,msbuild,grunt
Database managemant:DB deploy,flyway
Testing:selenuim,cucumber,junit
Deploy:
Deployment:ssh,octopus deploy
configure management/Provisioning: chef,puppet
Artifact management:Docker,python
Code quality analysis: Sonar quebe
Run:
Cloud/IAAS/Paas:aws
Orchestation & scheduling:kubernates,swarm
BI/Monitoring/Logging:logstash,kibana,grafana
Security:

Automation:
Auto Build:Make,Maven,Msbuild,gradle
Auto test:selenuim,cucumber,junit
Auto release:
Artifactory repository:jfrog/nexus
Obj Storage:S3
Container regestry:ECR
Auto deploy:terraform,vmware,cloud
Server provisoning:puppet,cheff,ansible,saltstack
Applcation Provisioning:Docker,fabric

Data points for devops:
quality trends:
quality dashboard:
overall health check:

DevOPs topics:
People perspctive
Process perspective
devops and agile
DevOps tools
Devops Life cycle
Maturity matrix:design&architech,build&deploy,test&QA,Information&Reporting,Culture&Organization.(base,essential,intermediate,advance,expert)
SCM GIT commnads:
SCM Remote repo:
SCM build continuous build:adhoc build,nightly build,CI build
build process maturity

continues inspection:
reduce code complexity
perform design reviews continuously
maintain organizational standerds with code audits
remove duplicate codes
Access code coverage


Chef:chef server,chef client,chef workstation.
chef recipie:
chef cookbooks : stores thr recipies or contains recipies,templates,files,custom resources.
chef run lists:collection of policies for the node to follow,chef-client get the run list from chef server
Manage complexity:
determine the desired infra
identify the resource to meet the state
gather resources into recipies
compose run list from receipies and roles
Apply runlist in each node in the env
Infra is configured according to the policy model in he cheff

Kubernates:lable mechanisem for idntity of pod
K8 api server configures & validate the data for each api objects like pod,controllers and services
end point contrller,replication control,name space controler
K8 scheduler manages to pods on cluster servers
master nodes & worker nodes pods are scheduled on worker nodes
kubelet is agent. to communicate each node with master
kube-proxy responsible networking be workers
Supports:
DNS
web Ui
container resourse monitoring 
cluster level logging
Kub objects:
Pods
kubernate service
kubernate volume. is storage resource traks failures and state of failure.
kubernate namespace
Controllers:
replica set
stateful set:
deamon set:
with in pod network system also with outside pod
withon pod shares ip and port btw containers using inter process communication
how to adopt old pods when loss replication controller using ner replication controller.using matching lable
