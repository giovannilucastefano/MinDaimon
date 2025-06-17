<%*
// Function to update index
async function updateIndex() {
    const dv = app.plugins.plugins.dataview.api;
    const notes = dv.pages("").sort(p => p.file.path);
    
    let output = "## Note Index\n\n";
    for (let n of notes) { 
        output += `- **${n.file.name}** (${n.file.path})\n`; 
    }
    
    await app.vault.adapter.write("MinDaimon/Service Notes/index.md", output);
}

// Update immediately on startup
await updateIndex();

// Set up periodic updates (every 2 minutes = 120000ms)
setInterval(updateIndex, 120000);
%>
