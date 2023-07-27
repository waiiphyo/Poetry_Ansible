## Prerequisites

1. Make sure you update [inventory](./inventory) file before running the playbook.

   For example, update node name and SSH host IP address.

   ```
   [web]
   ubuntu 
   ```

## Useful commands

**Playbook syntax check**
```bash
ansible-playbook -v --syntax-check main.yaml
```

**Run playbook**

```bash
ansible-playbook -v main.yaml
```

