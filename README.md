# PHP Docker Container
Dev container.

- PHP 7.2
- XDebug
- Composer
- Prestissimo Paralell Downloader
- Laravel Installer

## Usage

**Get image**  
`docket pull nicekiwi/php`

**Start container**  
`docker run -itd --rm -v $pwd:/opt/code -w /opt/code --network host --name php nicekiwi/php`  
  
**Enter container**  
`docker exec -it php bash`
