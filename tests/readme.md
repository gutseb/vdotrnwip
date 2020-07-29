try:

rm -rf /tmp/ansible.*; ansible-playbook -i inventory.yaml test.yml -v -e sat_api_password=password; find /tmp/ansible*