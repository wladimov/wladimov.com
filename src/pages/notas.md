---
layout: "../layouts/BlogPost.astro"
title: "Notas"
description: "Notas sobre desarrollo"
updatedDate: "Diciembre 19 2023"
heroImage: "https://images.pexels.com/photos/268351/pexels-photo-268351.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
---

## ¿Cómo borrar una branch de Git desde la terminal?
Borrar la branch local
```bash
git branch -d localBranchName
```
Borrar la branch remota
```bash
git push origin --delete remoteBranchName
```