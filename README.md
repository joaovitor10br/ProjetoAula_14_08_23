# Como criar um projeto do Node

npm init -y

# Instalar o typescript

npm install typescript --save-dev

# Inicializar e Configurar o typescript

```` npx tsc --init ````

# Formato do tsconfig.json recomendado:

  ````
  "compilerOptions": {
    "target": "es2016",
    "module": "commonjs",
    "rootDir": "./src",
    "outDir": "./dist",
    "esModuleInterop": true,
    "forceConsistentCasingInFileNames": true,
    "strict": true,
    "skipLibCheck": true
  }
}