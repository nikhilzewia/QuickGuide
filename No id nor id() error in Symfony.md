## No id nor id() error in Symfony
Use `'public'` for all table variables in Entity file
Example :

```javascript
<?php

// src/AppBundle/Entity/RedditPost.php

namespace App\Entity;

use Doctrine\ORM\Mapping as ORM;

/**
 * @ORM\Entity
 * @ORM\Table(name="larvel_users")
 */
class Users
{
    /**
     * @ORM\Column(type="integer")
     * @ORM\Id
     * @ORM\GeneratedValue(strategy="AUTO")
     */
    public $id;

    /**
     * @ORM\Column(type="string")
     */
    public $email;
    
    /**
     * @ORM\Column(type="string")
     */
    public $password;
    
}

?>
```
