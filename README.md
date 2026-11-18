# Ella Networks Claude Code Plugins

The [Claude Code](https://code.claude.com/) plugin marketplace of Ella Networks. Each plugin lives in its product's repository.

| Plugin | Product | Repository |
| --- | --- | --- |
| `ella-core` | [Ella Core](https://docs.ellanetworks.com/core/) | [ellanetworks/core](https://github.com/ellanetworks/core) |
| `ella-ims` | [Ella IMS](https://docs.ellanetworks.com/ims/) | [ellanetworks/ims](https://github.com/ellanetworks/ims) |
| `ella-smsc` | [Ella SMSC](https://docs.ellanetworks.com/smsc/) | [ellanetworks/smsc](https://github.com/ellanetworks/smsc) |
| `ella-mocn` | [Ella MOCN](https://docs.ellanetworks.com/mocn/) | [ellanetworks/mocn](https://github.com/ellanetworks/mocn) |

## Install

In Claude Code:

```
/plugin marketplace add ellanetworks/claude-plugins
/plugin install ella-core@ellanetworks
```

## Other agents

The skills follow the [Agent Skills](https://agentskills.io) standard. To use them with another agent, install them from the product's repository:

```
npx skills add ellanetworks/core
```

## License

Apache-2.0. Each plugin keeps the license of its own repository.
