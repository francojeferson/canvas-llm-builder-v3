# Canvas LLM Builder v3

## Phase 1: Project Setup & Database

### Step 1: Initialize Next.js Project

```bash
npx create-next-app@latest canvas-llm-builder --typescript --tailwind --eslint --app --src-dir --use-npm --import-alias "@/*"
cd canvas-llm-builder
```

### Step 2: Install Dependencies

```bash
# Install database-related dependencies
npm install drizzle-orm pg drizzle-kit dotenv @neondatabase/serverless

# Install core functional dependencies (React Flow, OpenAI SDK, UUID)
npm install reactflow openai uuid

# Install UI component libraries (Shadcn/UI related)
npm install @radix-ui/react-slot @radix-ui/react-dialog @radix-ui/react-label @radix-ui/react-separator class-variance-authority clsx tailwind-merge tailwindcss-animate lucide-react

# Install developer dependencies (types)
npm install -D @types/pg @types/uuid
```

### Step3: Initialize Shadnc/UI

```bash
npx shadcn@latest init
```

- Choose defaults (like default style, slate color). Set the components alias to @/components.

### Step4: Add Required Shadcn/UI Components

```bash
npx shadcn@latest add button input textarea label dialog separator sonner
```
