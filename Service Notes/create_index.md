<%*
const dv = app.plugins.plugins.dataview.api;
const notes = dv.pages("").sort(p => p.file.path);

let output = "## Note Index\n\n";
for (let n of notes) { 
    output += `- **${n.file.name}** (${n.file.path})\n`; 
}

// Write to Index.md in your vault
await app.vault.adapter.write("MinDaimon/Service Notes/index.md", output);
%>





