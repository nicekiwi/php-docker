# PHP Docker Container

![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/nicekiwi/php)

Dev container.

- PHP 7.2
- XDebug 2.7.0
- Composer (with Prestissimo and Laravel Installer)

## Usage

**Get image**   
`docket pull nicekiwi/php`

**Start container**  
`docker run -itd --rm -v $pwd:/opt/code -w /opt/code --network host --name php nicekiwi/php`

**Enter container**  
`docker exec -it php bash`

**Profit**  
`php echo 'Release the niffler!'`
