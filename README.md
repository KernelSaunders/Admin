# Sourcr

The solution to to finding a projects real traceability, supported by evidence and build for real use.

The problem we solve:
Products can come from every corner of world. Consumers may often be unaware truly where products are originated from. With so many product stages and complex production lines Sourcr aggregates the neccessary information to provide more informated decisions.

## Roles

- Testing - Pritch
- Game Design - H Alex
- Database Lead - Oliver
- Project Lead - Ben W
- Software Devs - Team
- Documentation and Comms - Shotton
- website - Shotton + Pritch

## Scrum link
[here](https://kernel-saunders.atlassian.net/jira/software/projects/SCRUM/boards/1)

# Backend

## Installation

1. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   # or
   venv\Scripts\activate     # Windows
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Install developer dependencies:
   ```bash
   pip install -r requirements-dev.txt
   ```

3. Create a `.env` file with your Supabase credentials:
   
   <https://supabase.com/dashboard/project/hvaudmnxzqkllqmrbzab/settings/api-keys>
   ```   
   SUPABASE_URL is the project id url
   SUPABASE_KEY can be either Publishable Key or Secret Key
   Publishable can be used in the frontend and uses row-level security (RLS) 
   Secret Key can be used in the backend and bypasses RL
   ```
    An example is in `.env.example`
   
## Running the API

Start the FastAPI server:

```bash
uvicorn src.main:app --reload
```

The API will be available at http://localhost:8000
Interactive API docs:
- Swagger UI: http://localhost:8000/docs
- ReDoc: http://localhost:8000/redoc

# Frontend
npm run dev

Next.js + React + Tailwind components

Could be worth using Shadcn as it has very good customizeability.

# Frontend

## Installation

1. Install dependencies:
   ```bash
   npm install
   ```


3. Create a `.env` file based of `.env.example`

## Running the local site

Start the dev server:

```bash
npm run dev
```

The site will be available at http://localhost:3000

## License

MIT License

Copyright (c) <YEAR> <COPYRIGHT HOLDER>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Contact Information
- Ben Pritchard bcp204@exeter.ac.uk
- Ben Worsley bw584@exeter.ac.uk
- Henry Alexander ha619@exeter.ac.uk
- Oliver Gregory og325@exeter.ac.uk
- William Wu qfw201@exeter.ac.uk
- Oliver Shotton os450@exeter.ac.uk
- Will Turner wtt201@exeter.ac.uk
