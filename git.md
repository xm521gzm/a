## 删除分支

---

git tag -l | awk '/v[1-2]{1}/{print}' | xargs git push origin --delete tag
git tag -l | awk '/v[1-2]{1}/{print}' | xargs git tag -d

JZK515wei

---

## 更换仓库地址

---

[git修改当前项目仓库地址的三种方法_git更换仓库地址_halo1416的博客-CSDN博客](https://blog.csdn.net/halo1416/article/details/123566471)