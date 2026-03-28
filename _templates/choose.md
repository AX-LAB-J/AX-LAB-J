<%*
const type = await tp.system.suggester(
  ["ML", "DL", "Agent", "Paper", "FastAPI", "Docker"],
  ["ml", "dl", "agent", "paper", "fastapi", "docker"]
)

await tp.file.include(`_templates/${type}.md`)
%>