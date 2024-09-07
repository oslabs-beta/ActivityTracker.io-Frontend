1. **Install npm package:**
   ```bash
   npm install os-analytics
   ```
2. **importing os-analytics:**
   ```bash
   import clickTracker from 'os-analytics';
   ```
3. **create a free account on os-analytics.com in order to receive an api key**
4. **using click tracker:**
  ```bash
   const apiKey = '2e0397b7-6cda-4806-8762-136d4a4591af'
   const website = 'test.com'
   clickTracker(apiKey, website)
   ```

**EXAMPLE USE CASE**
```bash
function App() {
  import clickTracker from 'os-analytics';

  const apiKey = '2e0397b7-6cda-4806-8762-136d4a4591af' //dummy data api key
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