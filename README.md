```rust
let me = Me {
  name: "Pedro",
  position: "Dev Fullstack",
  education: ["Análise e desenvolvimento de sistemas", "MBA - Engenharia de software"],
  stack: Stack {
    front: ["React", "React Native", "NextJs", "Flutter"],
    back:  ["Node", "Nestjs", "Rust", "Express" "Typescript", "RabbitMQ", "Kafka"],
    infra: ["Docker", "Kubernetes", "Ci/CD"],
    obeservability: ["Grafana", "Gray log"],
    cloud: ["AWS", "S3", "SQS", "Firebase"]
  },
  contact: Contact {
    email: "pedrocavallaro.contato@gmail.com",
    linkedin: "https://www.linkedin.com/in/pedro-cavallaro/"
  }
}

me.say("Welcome to my Github!");
```
