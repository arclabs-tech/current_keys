# Workstation Access Instructions

Hello,

You can access the workstations using the following SSH commands:

## ed25519 Key Users

### Windows
```
ssh -i C:\Users\<username>\.ssh\id_ed25519 -p 2222 mluser@10.3.32.55
```

### Mac
```
ssh -i ~/.ssh/id_ed25519 -p 2222 mluser@10.3.32.55
```

### Linux
```
ssh -i ~/.ssh/id_ed25519 -p 2222 mluser@10.3.32.55
```

## RSA Key Users

### Windows
```
ssh -i C:\Users\<username>\.ssh\id_rsa -p 2222 mluser@10.3.32.55
```

### Mac
```
ssh -i ~/.ssh/id_rsa -p 2222 mluser@10.3.32.55
```

### Linux
```
ssh -i ~/.ssh/id_rsa -p 2222 mluser@10.3.32.55
```

Thank You