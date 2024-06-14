- 👋 Hi, I’m @LILIBETH01
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
LILIBETH01/LILIBETH01 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

flowchart TD
    A[Proveedor emite factura] --> B[Proveedor entrega factura al Departamento de Contabilidad]
    B --> C[Departamento de Contabilidad registra la factura en el sistema contable]
    C --> D[Departamento de Contabilidad envía la factura al Gerente de Producción]
    D --> E[Gerente de Producción evalúa la factura]
    E --> |Conforme| F[Gerente de Producción firma y envía la factura a Caja para su pago]
    E --> |No conforme| G[Gerente de Producción devuelve la factura al Departamento de Contabilidad]
    G --> H[Departamento de Contabilidad descarga la factura no conforme del sistema contable]
    H --> I[Departamento de Contabilidad devuelve la factura al Proveedor]
