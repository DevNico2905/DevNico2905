<!-- ====== HEADER ====== -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=220&section=header&text=Nick%20Bernal&fontSize=70&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Backend%20Developer%20%E2%80%A2%20Java%20%26%20Spring%20Boot&descAlignY=58&descSize=20" />

<p align="center">
  <a href="https://github.com/DevNico2905">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=36BCF7&center=true&vCenter=true&width=650&lines=Construyo+APIs+con+Java+%2B+Spring+Boot+%E2%98%95;Despliego+en+AWS+%E2%98%81%EF%B8%8F;Tengo+un+cliente+real+en+producci%C3%B3n+%F0%9F%8E%B3;Antes+mezclaba+sonido+en+vivo+%F0%9F%8E%9B%EF%B8%8F;Rumbo+a+Cloud+Engineer+%F0%9F%9A%80" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://www.nick-bern.com"><img src="https://img.shields.io/badge/🌐_Portafolio-nick--bern.com-36BCF7?style=for-the-badge&labelColor=0f2027" /></a>
  <a href="https://www.linkedin.com/in/itsnicobernal"><img src="https://img.shields.io/badge/💼_LinkedIn-itsnicobernal-36BCF7?style=for-the-badge&labelColor=0f2027" /></a>
  <a href="mailto:bernalnico2905@gmail.com"><img src="https://img.shields.io/badge/✉️_Email-Escríbeme-36BCF7?style=for-the-badge&labelColor=0f2027" /></a>
</p>

<p align="center"><a href="./README.en.md">🇺🇸 Read in English</a></p>

---

## `GET /api/nick` 👨‍💻

```java
@RestController
@RequestMapping("/api/nick")
public class NickBernal {

    @GetMapping("/me")
    public Dev me() {
        return Dev.builder()
                .nombre("Nicolás Bernal")
                .rol("Backend Developer · Java & Spring Boot")
                .ubicacion("Rionegro, Antioquia 🇨🇴")
                .estudios("Ingeniería de Software @ U. de La Salle — 6.º semestre")
                .idiomas(List.of("Español (nativo)", "English (C1)"))
                .trabajando("Desarrollador independiente en nick-bern.com")
                .meta("Cloud Engineer ☁️")
                .build();
    }

    @GetMapping("/stack")
    public Map<String, List<String>> stack() {
        return Map.of(
            "backend",  List.of("Java", "Spring Boot", "JPA/Hibernate", "PostgreSQL", "MySQL", "Node.js"),
            "frontend", List.of("Angular", "TypeScript", "Tailwind CSS", "Flutter", "Electron"),
            "cloud",    List.of("AWS", "Docker", "Supabase", "Vercel", "CI/CD"),
            "extras",   List.of("n8n", "Resend", "Git", "Linux")
        );
    }

    @GetMapping("/aprendiendo")
    public List<String> aprendiendo() {
        return List.of(
            "Spring Boot + Hibernate a fondo",
            "AWS Certified Cloud Practitioner (preparando)",
            "Spec-Driven Development con IA"
        );
    }

    @GetMapping("/fun-fact")
    public String funFact() {
        return "Antes de programar mezclé sonido en vivo para +100 eventos 🎛️ — y aún canto y toco piano 🎹";
    }
}
```

---

## 🚀 Proyectos

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🎳 La Bolera Universo</h3>
      <img src="https://img.shields.io/badge/●_EN_PRODUCCIÓN-cliente_real-2ea44f?style=flat-square" /><br><br>
      Sistema de gestión y puntuación para una bolera en Neiva. Conseguí el cliente, negocié el contrato de alquiler con SLA y le doy soporte continuo.
      <br><br>
      <code>Angular</code> <code>Electron</code> <code>Supabase</code> <code>Tailwind</code>
      <br><br>
      <a href="https://bowlingdemo.nick-bern.com"><b>▶ Probar demo</b></a> · <a href="https://github.com/DevNico2905/bowling-app-demo">Repo del demo</a>
    </td>
    <td width="50%" valign="top">
      <h3>🌿 Mercado Páramo</h3>
      <img src="https://img.shields.io/badge/●_API_EN_VIVO-AWS-FF9900?style=flat-square" /><br><br>
      Venta directa entre pequeños productores de Guasca (páramo de Chingaza) y compradores, sin intermediarios. API REST con JWT desplegada en AWS.
      <br><br>
      <code>Java</code> <code>Spring Boot</code> <code>PostgreSQL</code> <code>JWT</code> <code>AWS</code>
      <br><br>
      <a href="https://api.mercadoparamo.nick-bern.com/swagger-ui/index.html"><b>▶ Ver Swagger</b></a> · <a href="https://github.com/DevNico2905/mercado-paramo">Repo</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🐾 VetTurno</h3>
      API para gestionar turnos de una veterinaria, proyecto evaluativo del curso <i>Java AI Engineer</i>.
      <br><br>
      <code>Java</code> <code>Spring Boot</code> <code>JPA/Hibernate</code>
      <br><br>
      <a href="https://github.com/DevNico2905/VetTurno">Repo</a>
    </td>
    <td width="50%" valign="top">
      <h3>☁️ Laboratorios AWS</h3>
      APIs Spring Boot en contenedores, API Gateway con Lambda Authorizer en Java, S3 + DynamoDB y CI/CD con CodePipeline → CodeBuild → Elastic Beanstalk.
      <br><br>
      <code>AWS</code> <code>Docker</code> <code>Lambda</code> <code>CI/CD</code>
    </td>
  </tr>
</table>

---

## 🏅 Certificaciones

| | |
|---|---|
| ☁️ **AWS Academy** | Machine Learning Foundations · Cloud Developing *(en curso)* |
| 🌐 **Cisco Networking Academy** | Introducción a las redes · Introducción a la ciberseguridad |

---

## 📈 Actividad

<p align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=DevNico2905&theme=tokyo-night&hide_border=true&area=true&bg_color=0d1117&color=36BCF7&line=36BCF7&point=ffffff" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=DevNico2905&theme=tokyonight&hide_border=true&background=0d1117&ring=36BCF7&fire=FF9900&currStreakLabel=36BCF7" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/DevNico2905/DevNico2905/output/github-snake-dark.svg" />
    <img alt="snake" src="https://raw.githubusercontent.com/DevNico2905/DevNico2905/output/github-snake.svg" />
  </picture>
</p>

<!-- ====== FOOTER ====== -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=120&section=footer" />
