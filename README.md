# Quick demo of config module behavior

https://www.npmjs.com/package/config

## USAGE

```
for X in dev test stage prod; do npm run test-$X; done
```

Output:

```
> @madisonlogic/config-test@1.0.0 test-dev /home/kangas/work/config-test
> NODE_ENV=development node .

Config { myEnvironment: 'development' }

> @madisonlogic/config-test@1.0.0 test-test /home/kangas/work/config-test
> NODE_ENV=test node .

Config { myEnvironment: 'test' }

> @madisonlogic/config-test@1.0.0 test-stage /home/kangas/work/config-test
> NODE_ENV=stage node .

Config { myEnvironment: 'stage' }

> @madisonlogic/config-test@1.0.0 test-prod /home/kangas/work/config-test
> NODE_ENV=production node .

Config { myEnvironment: 'production' }
```