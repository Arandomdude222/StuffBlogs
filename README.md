# DevStuff - Single-File PHP Blog System 
## LATEST: 1.0

![DevStuff Blog Screenshot](https://via.placeholder.com/800x400?text=DevStuff+Blog+Screenshot)

A lightweight, database-free blog system built with PHP in a single file. Perfect for personal blogs or small websites.

## Features

- 🚀 **No database required** - Flat-file storage (text files)  
- 📝 **Markdown support** - Write posts in Markdown  
- 🔐 **User management** - Admin & user roles  
- 🧩 **Plugin system** - Extend functionality  
- 📱 **Responsive design** - Works on all devices  
- 🔄 **Auto-update** - Built-in version checker  
- 🛡️ **Security** - Sanitized inputs, CSRF protection  

## Requirements

- PHP 7.4+ (with GD library for image handling)  
- Web server (Apache/Nginx)  
- Write permissions for the blog directory  

## Installation

1. **Upload files**:

   ```bash
   git clone https://github.com/yourusername/yourrepo.git
   ```
   Or download the ZIP and extract.

2. **Set permissions** if not set already:

   ```bash
   chmod -R 755 posts/ uploads/ cache/ plugins/
   ```

3. **Configure**:  
   Edit the top of `index.php`:

   ```php
   define('SITE_NAME', 'My Awesome Blog');
   define('BASE_URL', 'https://yourdomain.com');
   ```

4. **Access admin**:  
   Visit `/admin` on your site  
   Default credentials:

   ```
   Username: admin
   Password: admin123
   ```


## License

MIT License – See `LICENSE` file.

---

💻 Happy blogging! — [Demo](https://devstuff.lovestoblog.com) | [Issues](#)

---
