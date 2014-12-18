# my_lamp for Chef-solo
Chef-solo recipe to replace XAMPP.  
Only for non-production environment.  
**DO NOT** apply this cookbook to production environment.

## Environment
##### Virtual
- [CentOS 6.5 x86_64](https://github.com/2creatives/vagrant-centos/releases/tag/v6.5.3)
- Apache >= 2.2.0
- MySQL >= 5.6.0
- PHP >= 5.6.0
  - Composer
  - phpDocumnetor
  - yaml
  - Phalcon
- Node.js
  - JSDoc
- Git 2.2.0
- HerokuToolbelt

##### Host
- Windows 7 64bit
- VirtualBox
- Vagrant
- Chef-solo

## Note
ホスト、ゲスト双方の共有フォルダを変更しています。
```ruby
config.vm.synced_folder "../../server", "/var/www/html"
```

## Author
Yuusaku Miyazaki (toumin.m7@gmail.com)

## License
[MIT License](http://www.opensource.org/licenses/mit-license.php)