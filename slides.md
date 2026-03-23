---
theme: default
title: Manito — Pre-lanzamiento
info: Reunión interna 23.03.2026
highlighter: shiki
drawings:
  persist: false
transition: fade
mdc: true
fonts:
  sans: Inter
  weights: '400,600,700'
---

<div class="cover-layout">
  <div class="cover-left">
    <div class="cover-tag">MANITO</div>
    <h1 class="cover-title">Pre-<br>lanzamiento</h1>
    <p class="cover-sub">Roles, responsabilidades<br>y plan de trabajo</p>
    <div class="cover-date">23 · 03 · 2026</div>
  </div>
  <div class="cover-right">
    <div class="cover-dot-grid">
      <span v-for="i in 16" :key="i" class="dot" :class="i % 3 === 0 ? 'dot-coral' : 'dot-white'"></span>
    </div>
    <p class="cover-tagline">"Nosotros resolvemos."</p>
  </div>
</div>

---
layout: default
---

<SlideHeader title="Lo que viene" counter="1 / 3" />

<div class="timeline-grid">

<div class="phase-col">
  <div class="phase-header" style="background: var(--coral)">
    <div class="phase-title">Pre-lanzamiento</div>
    <div class="phase-dates">Ahora → 30 marzo</div>
  </div>
  <div class="phase-tag" style="color: var(--coral)">Esta semana</div>
  <div class="phase-body">
    <p>Cerrar el producto y dejarlo listo para el beta</p>
    <p>Preparar screenshots y descripciones para App Store y Play Store</p>
    <p>Armar los canales: Instagram, Facebook y WhatsApp Business</p>
    <p>Definir la lista de testers y preparar el mensaje de invitación</p>
  </div>
</div>

<div class="phase-col">
  <div class="phase-header" style="background: var(--mid-teal)">
    <div class="phase-title">Beta Cerrada</div>
    <div class="phase-dates">30 marzo → 13 abril</div>
  </div>
  <div class="phase-tag" style="color: var(--mid-teal)">2 semanas (sujeto a avance)</div>
  <div class="phase-body">
    <p>Testeo con personas cercanas: familia y amigos como clientes y profesionales</p>
    <p>Validar que todos los flujos de la app funcionen en condiciones reales</p>
    <p>Identificar y corregir bugs críticos antes del lanzamiento</p>
    <p>Ajustes finales al producto antes de abrir al público</p>
  </div>
</div>

<div class="phase-col">
  <div class="phase-header" style="background: var(--teal)">
    <div class="phase-title">Fase 1</div>
    <div class="phase-dates">Post 13 abril · 3–6 meses</div>
  </div>
  <div class="phase-tag" style="color: var(--teal)">Primeros meses</div>
  <div class="phase-body">
    <p>Campañas en Meta Ads para atraer a los primeros clientes</p>
    <p>Outreach a profesionales para sumar más proveedores al servicio</p>
    <p>Construir una base sólida de proveedores verificados</p>
    <p>Aprender con data real: qué funciona, qué hay que mejorar</p>
  </div>
</div>

</div>

---
layout: default
---

<SlideHeader title="Equipo y Responsabilidades" counter="2 / 3" />

<div class="team-section">

<div class="roles-row">
  <div class="role-card" style="--accent: var(--teal)">
    <div class="role-accent-bar"></div>
    <div class="role-name">Martín</div>
    <div class="role-title">Producto & Tech</div>
  </div>
  <div class="role-card" style="--accent: var(--coral)">
    <div class="role-accent-bar"></div>
    <div class="role-name">Matías</div>
    <div class="role-title">Marketing</div>
  </div>
  <div class="role-card" style="--accent: var(--mid-teal)">
    <div class="role-accent-bar"></div>
    <div class="role-name">Nacho</div>
    <div class="role-title">Legal</div>
  </div>
</div>

<div class="shared-label">Responsabilidad compartida entre todos</div>

<div class="shared-row">
  <div class="shared-block" style="background: var(--teal)">Finanzas &amp;<br>Contabilidad</div>
  <div class="shared-arrow">↔</div>
  <div class="shared-block" style="background: var(--mid-teal)">Operaciones</div>
  <div class="shared-arrow">↔</div>
  <div class="shared-block" style="background: var(--coral)">Ventas</div>
</div>

<div class="collab-label">Colaboradores</div>

<div class="collab-row">
  <div class="collab-card">
    <div class="collab-name">Germán</div>
    <div class="collab-desc">Maestro · Apoyo en conseguir proveedores</div>
  </div>
  <div class="collab-card">
    <div class="collab-name">Pome</div>
    <div class="collab-desc">Periodista · Apoyo en marketing y contenido</div>
  </div>
  <div class="collab-card">
    <div class="collab-name">Julie</div>
    <div class="collab-desc">Diseño gráfico e ilustraciones</div>
  </div>
</div>

</div>

---
layout: default
---

<SlideHeader title="Los 6 Pilares" counter="3 / 3" />

<div class="pillars-grid">

<div class="pillar-card">
  <div class="pillar-header" style="background: var(--teal)">
    <span class="pillar-title">Producto</span><span class="pillar-owner">Martín</span>
  </div>
  <ul>
    <li>Desarrollo y mantenimiento de la app (iOS y Android)</li>
    <li>QA, testeo y corrección de bugs</li>
    <li>Onboarding de clientes y profesionales</li>
    <li>Portal Controller: dashboard interno del equipo</li>
    <li>Roadmap y priorización de nuevas funcionalidades</li>
  </ul>
</div>

<div class="pillar-card">
  <div class="pillar-header" style="background: var(--coral)">
    <span class="pillar-title">Marketing</span><span class="pillar-owner">Matías</span>
  </div>
  <ul>
    <li>Campañas en Meta Ads para adquirir nuevos clientes</li>
    <li>Contenido orgánico y gestión de redes sociales</li>
    <li>Diseño de piezas y posts para Instagram y Facebook</li>
    <li>Edición de reels y contenido audiovisual</li>
    <li>Otros canales: WhatsApp y comunidades cercanas</li>
  </ul>
</div>

<div class="pillar-card">
  <div class="pillar-header" style="background: var(--mid-teal)">
    <span class="pillar-title">Legal</span><span class="pillar-owner">Nacho</span>
  </div>
  <ul>
    <li>Términos y condiciones (lado cliente y lado proveedor)</li>
    <li>Contrato de prestación de servicios</li>
    <li>Política de privacidad y protección de datos</li>
    <li>Código de conducta para proveedores</li>
    <li>Manual de disputas y resolución de conflictos</li>
  </ul>
</div>

<div class="pillar-card">
  <div class="pillar-header" style="background: var(--teal)">
    <span class="pillar-title">Finanzas</span><span class="pillar-owner">Entre todos</span>
  </div>
  <ul>
    <li>Modelo de comisiones y estructura de pagos</li>
    <li>Retención de boletas de honorarios e IVA</li>
    <li>Presupuesto mensual y control de gastos</li>
    <li>Unit economics: CAC, LTV y márgenes</li>
    <li>Seguros para los servicios prestados</li>
  </ul>
</div>

<div class="pillar-card">
  <div class="pillar-header" style="background: var(--coral)">
    <span class="pillar-title">Operaciones</span><span class="pillar-owner">Entre todos</span>
  </div>
  <ul>
    <li>Reclutamiento y verificación de proveedores</li>
    <li>Atención al cliente y resolución de conflictos</li>
    <li>Help center: preguntas frecuentes y guía de uso de la app</li>
    <li>Estándares de calidad, seguridad y conducta</li>
    <li>Balance de oferta y demanda por categoría</li>
  </ul>
</div>

<div class="pillar-card">
  <div class="pillar-header" style="background: var(--mid-teal)">
    <span class="pillar-title">Ventas</span><span class="pillar-owner">Entre todos</span>
  </div>
  <ul>
    <li>Captación de proveedores vía WhatsApp, correo y llamadas</li>
    <li>Onboarding y acompañamiento a nuevos proveedores</li>
    <li>Seguimiento y retención de proveedores activos</li>
    <li>Detección de gaps de oferta por categoría de servicio</li>
    <li>Coordinación con Germán para ampliar la red</li>
  </ul>
</div>

</div>

---
layout: default
---

<div class="closing-layout">
  <div class="closing-stripe"></div>
  <div class="closing-content">
    <div class="closing-tag">MANITO</div>
    <h2 class="closing-title">Ajustes y<br>comentarios</h2>
    <div class="closing-questions">
      <p>→ ¿Están de acuerdo con la distribución de responsabilidades?</p>
      <p>→ ¿Falta algo en alguno de los seis pilares?</p>
      <p>→ ¿Qué definimos hoy como próximo paso concreto?</p>
    </div>
    <div class="closing-tagline">"Nosotros resolvemos."</div>
  </div>
</div>
