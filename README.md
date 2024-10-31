# Sentiment News

[Sentiment News](https://sentiment-news.vercel.app) is a web app dedicated to exploring the relationship between financial news article sentiment and the price action of related stocks. The goal of this project was to quantify how positive or negative sentiment in news articles can influence stock price fluctuations. For example, when a news article about a company's success is published, the stock price of that company is expected to increase. This app creates insights into this phenomenon by analyzing news article sentiment and correlating it with stock price changes.

## Frontend Tech Stack

- TypeScript
- Next.js
- TailwindCSS

## Backend Tech Stack

- Python
- FastAPI
- Tortoise-ORM
- PostgreSQL

## APIs Used

- [RapidAPI](https://rapidapi.com/hub)
- [Finnhub](https://finnhub.io/)
- [Tinngo](https://www.tiingo.com/)
- [Gemini](https://ai.google.dev/)
- [Postgres](https://supabase.com/)

## Frontend Start

First, install the dependencies:

```bash
npm install
# or
yarn
# or
pnpm install
```

Then, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Backend Setup

1. Clone the repo

```shell
git clone https://github.com/bagus0300/Sentiment-News-Backend.git
```

2. Create virtual environemnt

```shell
cd server

python3 -m venv venv

# Windows
venv\Scripts\activate

# Mac
source venv/bin/activate
```

3. Install requirements

```shell
pip install -r requirements.txt
```

4. Get free API keys and fill in values in `.env`

- [RapidAPI](https://rapidapi.com/hub)
- [Finnhub](https://finnhub.io/)
- [Tinngo](https://www.tiingo.com/)
- [Gemini](https://ai.google.dev/)
- [Postgres](https://supabase.com/)

## Running

```shell
hypercorn src/main:app --reload
```
