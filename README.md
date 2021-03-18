**ReadMe:**

*[Requirements for tower management:]{.ul}*

1.  Install Tower collection:

> ansible-galaxy collection install awx.awx

2.  Add Repo for Tower-cli:

> dnf config-manager \--add-repo
> [[https://releases.ansible.com/ansible-tower/cli/ansible-tower-cli-el8.repo]{.ul}](https://releases.ansible.com/ansible-tower/cli/ansible-tower-cli-el8.repo)

3.  Install ansible-tower-cli:

> dnf install ansible-tower-cli

4.  If RHEL 8 use the epel8:

> yum install
> https://dl.fedoraproject.org/pub/epel/epel-release-latest-8.noarch.rpm

5.  Install Python-pip:

> dnf install python2-pip
>
> dnf install python3-pip

6.  Install ansible-tower-cli using python-pip:

> pip2 install ansible-tower-cli
>
> pip3 install ansible-tower-cli

7.  Configure tower-cli:

> tower-cli config username "username"
>
> tower-cli config password redhat
>
> tower-cli config host "host"

*[Requirements for tower management:]{.ul}*

1.  Install Tower collection:

> ansible-galaxy collection install community.windows

To be Continued\...
