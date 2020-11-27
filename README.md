# backup-wordpress
A single PHP script for backing up WordPress into a .zip

```php
/**
 * Single file backup of a WordPress site, suitable for dropping in FlyWheel Local
 * or restoring just about anywhere.
 * 
 * @author   Nick Temple <nick@nicktemple.com>
 * @license  http://www.gnu.org/copyleft/gpl.html GNU General Public License
 * @link     https://github.com/ifsnop/mysqldump-php
 *
 * See additional credits inline.
 * MysqlDump:
 * @author   Diego Torres <ifsnop@github.com>
 * 
 * 1) drop this file into your WordPress folder
 * 2) run php migrate.php
 * 3) the migrate.zip will contain a backup of the database and all files below this folder. 
 * 4) DELETE migrate.php and migrate.sql as soon as you are done.
 * 5) move migrate.zip to wherever you need the backup.
 * 
 */
```
