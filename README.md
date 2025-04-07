# ActuBot

![ActuBot Logo](https://via.placeholder.com/500x100?text=ActuBot)

> GPT-powered intelligent assistant for actuarial report analysis and exploration

## 🚀 Overview

ActuBot transforms complex actuarial reports into accessible, interactive knowledge bases. Upload your PDF or Word actuarial documents and interact with them through natural language queries to extract insights, identify trends, and understand complex actuarial concepts without requiring deep domain expertise.

### Key Features

- **Intelligent Document Processing**: Upload actuarial reports and have key metrics, tables, and insights automatically extracted
- **Natural Language Queries**: Ask questions about the report in plain English, such as "What caused the reserve strengthening in 2021?"
- **Contextual Understanding**: Get answers that consider the full context of the document, with citations to source material
- **Data Visualization**: Automatically generate visual representations of key metrics and trends
- **Secure & Private**: End-to-end encryption and robust access controls to protect sensitive information

## 🧰 Tech Stack

<table>
  <tr>
    <td align="center" width="33%"><strong>Frontend</strong></td>
    <td align="center" width="33%"><strong>Backend</strong></td>
    <td align="center" width="33%"><strong>AI/ML</strong></td>
  </tr>
  <tr>
    <td>
      <ul>
        <li>Next.js</li>
        <li>Tailwind CSS</li>
        <li>React</li>
        <li>Chart.js</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>Node.js</li>
        <li>Supabase</li>
        <li>PostgreSQL</li>
        <li>Redis</li>
      </ul>
    </td>
    <td>
      <ul>
        <li>LangChain/LlamaIndex</li>
        <li>Gemini 2.5 Pro</li>
        <li>Vector Embeddings</li>
        <li>OCR Processing</li>
      </ul>
    </td>
  </tr>
</table>

## 📋 Use Cases

- **Actuaries**: Quickly reference specific calculations and methodologies across large reports
- **Insurance Professionals**: Extract key insights without deep actuarial expertise
- **Executives**: Get high-level summaries and answer strategic questions
- **Analysts**: Compare metrics across different time periods and reports
- **Auditors**: Verify calculations and methodological consistency

## 🛠️ Getting Started

### Prerequisites

- Node.js 18.x or higher
- npm or yarn
- Supabase account
- Gemini API key

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/actubot.git
cd actubot
```

2. Install dependencies
```bash
npm install
# or
yarn install
```

3. Set up environment variables
```bash
cp .env.example .env.local
```
Edit `.env.local` with your Supabase and Gemini API credentials.

4. Run the development server
```bash
npm run dev
# or
yarn dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser

## 🔐 Security & Compliance

ActuBot is designed with security and compliance in mind:

- End-to-end encryption for sensitive data
- Role-based access control
- Audit logging of all system activities
- GDPR and CCPA compliant data handling
- SOC 2 compliance roadmap

## 🧩 Architecture

```
                 ┌──────────────────┐
                 │    Client UI     │
                 │    (Next.js)     │
                 └────────┬─────────┘
                          │
                          ▼
┌──────────────┐  ┌──────────────────┐  ┌──────────────┐
│              │  │                  │  │              │
│   Supabase   │◄─┤   API Routes     │──┤ Gemini 2.5   │
│  (Auth/DB)   │  │   (Next.js)      │  │     Pro      │
│              │  │                  │  │              │
└──────────────┘  └────────┬─────────┘  └──────────────┘
                          │
                          ▼
                 ┌──────────────────┐
                 │  LangChain or    │
                 │   LlamaIndex     │
                 └──────────────────┘
```

## 📄 Documentation

- [User Guide](docs/user-guide.md)
- [API Documentation](docs/api.md)
- [Development Guide](docs/development.md)
- [Architecture Decision Records](docs/adr)

## 🚧 Roadmap

- [ ] Multi-document analysis
- [ ] Advanced visualization library
- [ ] Collaborative features
- [ ] Mobile application
- [ ] API for third-party integrations
- [ ] Custom report templates

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and development process.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgements

- [Next.js](https://nextjs.org/)
- [Supabase](https://supabase.io/)
- [LangChain](https://langchain.com/)
- [LlamaIndex](https://www.llamaindex.ai/)
- [Gemini](https://ai.google.dev/gemini-api)

---

<p align="center">
  <sub>Built with ❤️ by [Your Company/Team Name]</sub>
</p>
