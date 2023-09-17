# User Agent PHP Class
User Agent Class to help identify browser, platform, robot, and mobile device data.

## How to use?
``` bash
$user_agent = new Client_User_Agent;
```

1. To get browser:
``` bash
$user_agent->getBrowser();
```

2. To get mobile:
``` bash
$user_agent->getMobile();
```

3. To get Platform:
``` bash
$user_agent->getPlatform();
```

4. To get referrer:
``` bash
$user_agent->getReferrer();
```
