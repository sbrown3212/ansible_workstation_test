# ansible_workstation_test

Testing with Ansible for configuring workstation desktops and laptops. Designed to be used with the `ansible-pull` command locally on the machine that is to be configured (unlike remotely from an Ansible server).

This is a work in progress. The intention is to be able to configure my MacOS and Linux machines with `ansible-pull`.

## How To Use

1. Ensure `ansible` is installed.
On MacOS:

```
brew install anisible
```

On Linux:

```
pip install ansible
```

2. To run:

```
sudo ansible-pull -U https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME.git
```

## Resources

- Learn Linux Tv's video on setting up laptops and desktops (TODO: get link to video)

### Resources to look into

- Jeff Geerling's [Ansible Dev Playbook]() (TODO: get link to playbook)
- Learn Linux Tv's vido on `ansible-pull` (TODO: get link to video)
- Jeff Geerling's YouTube playlist on Ansible 101(?) (TODO: get link to playlist)
- Learn Linux Tv's YouTube playlist on ansible (TODO: get link to playlist)
- YouTube [video](https://youtu.be/hPPIScBt4Gw?si=Oj4J-2v7rdPSkURW) on multi OS workstation ansible playbook.
