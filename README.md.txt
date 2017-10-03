…or create a new repository on the command line

echo "# testgit1" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/toihd/testgit1.git
git push -u origin master
…or push an existing repository from the command line

git remote add origin https://github.com/toihd/testgit1.git
git push -u origin master
…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

2.Muốn push cái gì lên git web thì trước tiên phải add nó vào trạng thái sẵn sàng đc push lên git web , bằng git add ... nếu ko thì push nó sẽ ko lên đc. git add trước và git push
