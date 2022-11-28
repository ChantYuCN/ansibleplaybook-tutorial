# ansibleplaybook-tutorial


## setup clean env 

```console
mkdir python-venv
cd !$
python3 -m venv ansible2.10
source ansible2.10/bin/activate

python3 -m pip install --upgrade pip
python3 -m pip install ansible==2.10.0


source ansible2.10/bin/activate
ansible-playbook  -i production  bootstrap.yml
deactivate
```


