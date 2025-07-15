export default function TerapiasPage() {
  return (
    <div className="min-h-screen bg-white text-gray-800 px-4 py-8 md:px-16">
      <h1 className="text-4xl font-bold mb-6 text-center">Terapias Disponibles</h1>
      <p className="text-center text-lg mb-10">
        📍 Calle Coruña N14 Bajo, Baltar, Sanxenxo<br />
        🕒 Lunes a Viernes: 8:00–13:00 / 15:00–21:00<br />
        📲 Reserva por WhatsApp: <a href="https://wa.me/34638728766" className="text-blue-600 underline">638728766</a>
      </p>

      <div className="grid gap-10 md:grid-cols-2 lg:grid-cols-3">
        {terapias.map((terapia, index) => (
          <div key={index} className="rounded-2xl shadow-md overflow-hidden bg-gray-50">
            <img src={terapia.imagen} alt={terapia.nombre} className="w-full h-64 object-cover" />
            <div className="p-4">
              <h2 className="text-xl font-semibold mb-2">{terapia.nombre}</h2>
              <p className="text-gray-600 text-sm">{terapia.descripcion}</p>
            </div>
          </div>
        ))}
      </div>
    </div>
  );
}

const terapias = [
  {
    nombre: "Quiromasaje",
    imagen: "https://example.com/quiromasaje.jpg",
    descripcion:
      "Técnica manual que alivia contracturas, mejora la circulación y proporciona relajación profunda. Ideal para el dolor muscular y el estrés.",
  },
  {
    nombre: "Tuina",
    imagen: "https://example.com/tuina.jpg",
    descripcion:
      "Masaje terapéutico chino basado en la Medicina Tradicional China. Estimula puntos energéticos para equilibrar cuerpo y mente.",
  },
  {
    nombre: "Reflexología Podal",
    imagen: "https://example.com/reflexologia.jpg",
    descripcion:
      "Masaje específico en los pies que estimula órganos internos y promueve el bienestar general. Ideal para el estrés, la digestión y el sueño.",
  },
  {
    nombre: "Acupuntura",
    imagen: "https://example.com/acupuntura.jpg",
    descripcion:
      "Inserción de agujas finas en puntos clave para desbloquear la energía del cuerpo. Eficaz para dolores crónicos, ansiedad y más.",
  },
  {
    nombre: "Moxibustión",
    imagen: "https://example.com/moxibustion.jpg",
    descripcion:
      "Aplicación de calor con moxa (planta artemisa) en puntos energéticos. Estimula la circulación y refuerza el sistema inmunológico.",
  },
  {
    nombre: "Ventosas",
    imagen: "https://example.com/ventosas.jpg",
    descripcion:
      "Terapia de succión con copas que mejora la circulación y libera tensiones musculares. Muy usada en medicina deportiva y relajación.",
  },
];


Aquí tienes una página web moderna y clara que presenta las terapias disponibles en tu consulta en Sanxenxo. Incluye:

Título llamativo

Información de contacto y horarios

Sección en cuadrícula con imagen, nombre y descripción de cada terapia


Si deseas añadir más terapias, cambiar el estilo, enlazar con redes sociales o integrar un sistema de reservas, puedo ayudarte. ¿Quieres que lo preparemos para publicar en línea?

