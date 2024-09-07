1. **Install npm package:**
   ```bash
   npm install os-analytics
   ```
2. **Importing os-analytics:**
   ```bash
   import clickTracker from 'os-analytics'
   ```
3. **Create a free account on os-analytics.com in order to receive an api key**
4. **Using click tracker:**
  ```bash
   const apiKey = '2e0397b7-6cda-4806-8762-136d4a4591af'
   const website = 'test.com'
   clickTracker(apiKey, website)
   ```

**EXAMPLE USE CASE**
```bash
function App() {
  import clickTracker from 'os-analytics';

  const apiKey = '2e0397b7-6cda-4806-8762-136d4a4591af' //dummy api key
  const website = 'test.com'

  clickTracker(apiKey, website);

 return (
    <div className="app">
      <h1>OS Analytics Demo</h1>
      <div className="button-row">
        <HeatButton name="Button 1" />
        <HeatButton name="Button 2" />
        <HeatButton name="Button 3" />
      </div>
    </div>
  );
}

export default App;
```

**Refresh your dashboard on os-analytics and you should see click data for your website!**