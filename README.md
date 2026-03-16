```ts
/**
 * Jakub Maksymowicz — Full-Stack Web Developer
 * "Code is the modern dialect."
 */

type Developer = {
  name: string
  location: string
  main_stack: string[]
  learning: string[]
  projects: string[]
  infrastructure: string[]
}

class Jakub implements Developer {

  name = "Jakub Maksymowicz"
  location = "Wolsztyn, Poland"

  main_stack = [
    "JavaScript",
    "TypeScript",
    "Node.js",
    "React",
    "Vite"
  ]

  learning = [
    "Python",
    "System Architecture",
    "High performance backend"
  ]

  infrastructure = [
    "Proxmox",
    "Linux",
    "Self-hosted services",
    "Zabbix"
  ]

  projects = [
    "klovy.xyz — personal portfolio",
    "klovy.pl — education project",
    "Klovy Chat — modern communication platform"
  ]

  status() {
    console.log("Building modern web applications and infrastructure.")
  }
}

const dev = new Jakub()
dev.status()
```
