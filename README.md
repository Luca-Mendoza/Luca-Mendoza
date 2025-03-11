import WebDeveloper from 'mendozaluca';

class Bio extends WebDeveloper {
  name     = 'Luca Alberto Daniel';
  lastname = 'Mendoza';
  title    = 'Frontend Web Developer';
  company  = 'Siete Ideas';
  location = 'Tandil, Buenos Aires, Argentina';
}

class Skills extends WebDeveloper {
  languages  = ['HTML5', 'CSS3', 'JavaScript', 'TypeScript'];
  frameworks = [
    { JavaScript: ['Angular'] },
    { CSS3: ['Material Angular', 'Bootstrap', 'TailwindCSS'] }
  ];
  stateManagement = ['Redux - NgRx'];
  tools      = ['Git', 'GitHub', 'GitLab', 'Trello', 'Postman', 'MongoDB Compass'];
}

class Experience extends WebDeveloper {
  jobs = [
    {
      company: 'Siete Ideas',
      role: 'SSR Frontend Developer',
      period: '2022 - Presente',
      tasks: [
        'Desarrollo y mantenimiento de aplicaciones en Angular.',
        'Creación de interfaces modernas y responsivas.',
        'Integración de APIs REST y pruebas unitarias con Jasmine/Karma.'
      ]
    },
    {
      company: 'Event Loop Club',
      role: 'Cofundador & SSR Frontend Developer',
      period: '2023 - Presente',
      tasks: [
        'Desarrollo de aplicaciones web escalables.',
        'Gestión de estado global con NgRx.',
        'Optimización de rendimiento en aplicaciones Angular.'
      ]
    }
  ];
}

class Projects extends WebDeveloper {
  featured = [
    {
      name: 'E-commerce MEAN + GraphQL',
      stack: ['MongoDB', 'Express.js', 'Angular', 'Node.js'],
      features: ['Integración con Stripe', 'Notificaciones con Nodemailer']
    },
    {
      name: 'Portfolio Web',
      stack: ['Angular', 'Angular Material'],
      features: ['Diseño moderno', 'Optimización para performance']
    }
  ];
}

class Contact extends WebDeveloper {
  github   = 'https://github.com/Luca-Mendoza';
  linkedin = 'https://www.linkedin.com/in/luca-d-mendoza-470575180/';
  email    = 'mendoza.d.luca@gmail.com';
}
