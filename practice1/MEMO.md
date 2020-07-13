# SSH Password ログイン
ansible-playbook -i inventory playbook.yml -u <username> -k

# ERROR! to use the 'ssh' connection type with passwords, you must install the sshpass program
sshpassをインストール
'''sudo apt-get install sshpass'''
