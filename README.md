# ansible-guide
Learn what is Ansible

Playbooks
 * Tasks are executed sequentially invoke Ansible modules
Modules
 * executable bit of code makes the work check the guide for more syntax
Plugins - Gears in the engine
 * Code that plus into the core engine adaptability for various use and platforms. You can write your own plugins
Inventory
 * List of systems in your infrastructure that automation is executed against. it connects using SSH
Cloud
 * Can pull from Cloud.
CMDB
 * hot to manage and it pull module and work using inventory
Automate Everything
 * Anything to do with Ansible

Ad-hoc Commands
 * without playbook
Inventory
 * collection of systems you going to work with
 ** Host
 ** Groups
 ** inventory-specific data(variables)
 ** static or dynamic sources

Playbook:
 * Configuration deployment and Orchestration language
 * setup of

Modules are tools in your workshop
Playbooks are instruction manuals
Target host are raw materials

Best Practices:
 * Simplicity makes it simple and straightforward
 * Make it simple and small. Do not clutter
 * do not forget to use `name` for explanatory tasks
 * Use alias names in inventory
 * Dynamic inventories - Stay in sync automatically - Reduce human errors
 * Know YAML syntax! this is your language!
 * use > if you use multiline. format properly make it better readable
 * User variable if you have resentment values - reuse and refactoring Avoid Python escape characters!
 *`ansible-playbook playbook.yml --syntax-check`
 * use linter

Roles:
 * Think about the full life-cycle of a service, microservice or container - not a whole stack or environment
 * Keep provisioning separate from configuration and app deployment
 * Roles are not classes or objects or libraries - those are programming constructs
 * Keep roles loosely-coupled-limit hard dependencies on other roles or external variables
