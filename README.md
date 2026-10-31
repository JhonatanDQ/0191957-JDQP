# 0191957-Jhonatan David Quiroga Perez

Proyecto del taller de Cloud Computing (Ingeniería de Sistemas – UFPSO).

Despliega automáticamente en AWS una instancia EC2 con Apache y una página web
personalizada. La infraestructura está definida en `templates/template.yaml`
(CloudFormation) y el despliegue lo ejecuta GitHub Actions
(`.github/workflows/deploy.yml`) cada vez que se hace push a la rama `main`.

## Estructura

- `.github/workflows/deploy.yml`: flujo de GitHub Actions
- `templates/template.yaml`: plantilla de CloudFormation (EC2 + Security Group + User Data)
- `README.md`

## Estudiante

- Nombre:  Jhonatan David Quiroga Perez
- Código: 0191957
- Docente: Wilder Andrés Duarte Neira

