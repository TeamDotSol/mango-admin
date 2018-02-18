# Mango CLI

```
Leon's private key.
leondo$ PRIVATE_KEY=505bdbc30b8f84d06dbfb4c780a5504c87a2a13731f11c41c0f9b4247b719985 ADDRESS=0x5873E7b7F909B4F76ce4B7B3338DB674F1aC3a02 mango-admin create
```

A commandline tool for Mango.  Supports repository creation and management.  It works like Github for repositories.  See the main [Mango](https://github.com/axic/mango) repository for further explanation.

## Usage

### Create a repository

```
PRIVATE_KEY=505bdbc30b8f84d06dbfb4c780a5504c87a2a13731f11c41c0f9b4247b719985 ADDRESS=0x5873E7b7F909B4F76ce4B7B3338DB674F1aC3a02 CONTRACT_ADDRESS=0xd23a85416c6aC45D7f3d3D04BD4791c0346CCE8F mango-admin create --name repoName
```

### List all repositories

```
$ PRIVATE_KEY=505bdbc30b8f84d06dbfb4c780a5504c87a2a13731f11c41c0f9b4247b719985 ADDRESS=0x5873E7b7F909B4F76ce4B7B3338DB674F1aC3a02 mango-admin --repo 0xd23a85416c6aC45D7f3d3D04BD4791c0346CCE8F list
```

### Push a repositories

```
$ PRIVATE_KEY=505bdbc30b8f84d06dbfb4c780a5504c87a2a13731f11c41c0f9b4247b719985 ADDRESS=0x5873E7b7F909B4F76ce4B7B3338DB674F1aC3a02 mango-admin push --directory ./
```
