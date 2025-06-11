<div align="center">
  <img width="100px" alt="logo" src="https://cdn.jsdelivr.net/gh/alist-org/logo@main/logo.svg"/></a>
  <p><em>🗂️A file list program that supports multiple storages, powered by Gin and Solidjs.</em></p>
<div>

---

> [!IMPORTANT]
>
> 本 Fork 尚未稳定, 大量外部链接指向的内容尚未得到审计, 存在投毒风险, 含相关文档网站等. 切勿盲目信任!
>
> This fork is not yet stable. A large number of external links point to unaudited content, posing a supply chain attack risk, including related documentation websites, etc. Do not trust!
>
> 目前仅移除了确认非原作者控制的相关链接 (如 `alistgo.com`)
>
> Currently, only links confirmed to be outside the original author's control (such as `alistgo.com`) have been removed.
>
> 请您为确认本 Fork 新名字投票: https://github.com/AlistTeam/alist/issues/4
>
> Please vote to determine the name: https://github.com/AlistTeam/alist/issues/4

English | [中文](./README_cn.md) | [日本語](./README_ja.md) | [Contributing](./CONTRIBUTING.md) | [CODE_OF_CONDUCT](./CODE_OF_CONDUCT.md)

## Features

- [x] Multiple storages
    - [x] Local storage
    - [x] [Aliyundrive](https://www.alipan.com/)
    - [x] OneDrive / Sharepoint ([global](https://www.office.com/), [cn](https://portal.partner.microsoftonline.cn),de,us)
    - [x] [189cloud](https://cloud.189.cn) (Personal, Family)
    - [x] [GoogleDrive](https://drive.google.com/)
    - [x] [123pan](https://www.123pan.com/)
    - [x] FTP / SFTP
    - [x] [PikPak](https://www.mypikpak.com/)
    - [x] [S3](https://aws.amazon.com/s3/)
    - [x] [Seafile](https://seafile.com/)
    - [x] [UPYUN Storage Service](https://www.upyun.com/products/file-storage)
    - [x] WebDav(Support OneDrive/SharePoint without API)
    - [x] Teambition([China](https://www.teambition.com/ ),[International](https://us.teambition.com/ ))
    - [x] [Mediatrack](https://www.mediatrack.cn/)
    - [x] [139yun](https://yun.139.com/) (Personal, Family, Group)
    - [x] [YandexDisk](https://disk.yandex.com/)
    - [x] [BaiduNetdisk](http://pan.baidu.com/)
    - [x] [Terabox](https://www.terabox.com/main)
    - [x] [UC](https://drive.uc.cn)
    - [x] [Quark](https://pan.quark.cn)
    - [x] [Thunder](https://pan.xunlei.com)
    - [x] [Lanzou](https://www.lanzou.com/)
    - [x] [ILanzou](https://www.ilanzou.com/)
    - [x] [Aliyundrive share](https://www.alipan.com/)
    - [x] [Google photo](https://photos.google.com/)
    - [x] [Mega.nz](https://mega.nz)
    - [x] [Baidu photo](https://photo.baidu.com/)
    - [x] SMB
    - [x] [115](https://115.com/)
    - [X] Cloudreve
    - [x] [Dropbox](https://www.dropbox.com/)
    - [x] [FeijiPan](https://www.feijipan.com/)
    - [x] [dogecloud](https://www.dogecloud.com/product/oss)
    - [x] [Azure Blob Storage](https://azure.microsoft.com/products/storage/blobs)
- [x] Easy to deploy and out-of-the-box
- [x] File preview (PDF, markdown, code, plain text, ...)
- [x] Image preview in gallery mode
- [x] Video and audio preview, support lyrics and subtitles
- [x] Office documents preview (docx, pptx, xlsx, ...)
- [x] `README.md` preview rendering
- [x] File permalink copy and direct file download
- [x] Dark mode
- [x] I18n
- [x] Protected routes (password protection and authentication)
- [x] WebDav (see https://alist.nn.ci/guide/webdav.html for details)
- [ ] ~~Docker Deploy~~
- [x] Cloudflare Workers proxy
- [x] File/Folder package download
- [x] Web upload(Can allow visitors to upload), delete, mkdir, rename, move and copy
- [x] Offline download
- [x] Copy files between two storage
- [x] Multi-thread downloading acceleration for single-thread download/stream

## Document

N/A

## Demo

N/A

## Discussion

Please go to our [discussion forum](https://github.com/AlistTeam/alist/discussions) for general questions, **issues are for bug reports and feature requests only.**

## Contributors

Thanks goes to those wonderful people:

[![Contributors](http://contrib.nn.ci/api?repo=alist-org/alist&repo=alist-org/alist-web&repo=alist-org/docs)](https://github.com/alist-org/alist/graphs/contributors)

## License

The `AList` was open-source software licensed under the AGPL-3.0 license.

## Disclaimer
- This program is a free and open source project. It is designed to share files on the network disk, which is convenient for downloading and learning Golang. Please abide by relevant laws and regulations when using it, and do not abuse it;
- This program is implemented by calling the official sdk/interface, without destroying the official interface behavior;
- This program only does 302 redirect/traffic forwarding, and does not intercept, store, or tamper with any user data;
- Before using this program, you should understand and bear the corresponding risks, including but not limited to account ban, download speed limit, etc., which is none of this program's business;

---

> [@GitHub](https://github.com/AlistTeam)
