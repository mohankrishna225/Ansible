<h4 id="install-ansible-for-linux">Install ansible for linux</h4>
<ul>
<li>sudo yum update -y</li>
<li>sudo yum install -y python-boto python-boto3</li>
<li>sudo rpm -Uvh <a href="https://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm">https://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm</a></li>
<li>sudo amazon-linux-extras install ansible2 -y  # for amazon-linux2</li>
<li>sudo yum install ansible -y</li>
</ul>
<h4 id="install-ansible-on-a-mac">Install ansible on a Mac</h4>
<ul>
<li>Check if pip is already installed in your mac (which pip). In case you don’t have it, try sudo easy_install pip</li>
<li>For installing Ansible, use : sudo pip install ansible</li>
<li>Another alternative to install ansible is using brew, you can simply do --&gt; brew install ansible.</li>
</ul>
<h4 id="install-ansible-on-windows">Install ansible on Windows</h4>
<ul>
<li>The easiest solution for installing ansible on windows is to use a linux virtual machine. for instance- virtualbox, vmware</li>
</ul>
<h4 id="for-rhelcentos-systems">For RHEL/CentOS systems</h4>
<ul>
<li>python-pip and ansible are available via the EPEL repository.</li>
<li>In order to see if EPEL repo is already available, use command–&gt; yum repolist | grep epel</li>
<li>use this command for RHEL/CentOS 6–&gt; rpm -ivh <a href="http://d1.fedoraproject.org/pub/epel/6/x86_64/%5C">http://d1.fedoraproject.org/pub/epel/6/x86_64/\</a>     epel-release-6.8.noarch.rpm</li>
<li>For RHEL/Centos7 use–&gt; yum install epel-release</li>
</ul>
<h4 id="for-debianubuntu">For Debian/Ubuntu</h4>
<ul>
<li>sudo apt-get install python-software-properties</li>
<li>sudo apt-add-repository -y ppa:ansible/ansible</li>
<li>sudo apt-get update</li>
<li>sudo apt-get install -y ansible</li>
</ul>
<h4 id="once-installed-use-ansible---version-to-verify">Once installed, use ansible --version (to verify)</h4>

