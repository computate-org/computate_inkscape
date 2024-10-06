
# Install the prerequisite applications

- https://github.com/computate-org/computate_potrace

# Install inkscape

### Create a directory for the ansible role. 

```bash
install -d ~/.ansible/roles/computate.computate_inkscape
```

### Clone the inkscape ansible role. 

```bash
git clone git@github.com:computate-org/computate_inkscape.git ~/.ansible/roles/computate.computate_inkscape
```

## Run the inkscape ansible playbook to install the application locally. 

```bash
cd ~/.ansible/roles/computate.computate_inkscape
ansible-playbook install.yml
```

