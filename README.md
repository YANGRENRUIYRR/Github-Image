# Github-Image
图像托管解决方案，Flickr/imgur的替代方案，使用户可以轻松分享他们的图像。使用Vercel和Github。

先Fork本仓库，然后使用Vercel部署，最后配置Vercel环境变量`GITHUB_USERNAME`为Github用户名、`GITHUB_REPO`为空仓库（新建一个）的仓库名、`GITHUB_TOKEN`为Github的一个Token，要有repo的所有权限。

空仓库可以自行部署（建议不要用Vercel部署，每天只能上传100张），以免Github不能访问，部署后请自行修改api/upload.ts。
