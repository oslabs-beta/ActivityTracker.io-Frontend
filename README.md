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

**EXAMPLE USE CASE (React)**
```bash
import clickTracker from 'os-analytics';

function App() {
  const apiKey = '2e0397b7-6cda-4806-8762-136d4a4591af' //dummy api key
  const website = 'test.com'

  clickTracker(apiKey, website);

 return (
    <div className="app">
      <h1>OS Analytics Demo</h1>
      <div className="button-row">
        <button name="Button 1">Button 1</button>
        <button name="Button 2">Button 2</button>
        <button name="Button 3">Button 3</button>
      </div>
    </div>
  );
}

export default App;
```

**Refresh your dashboard on os-analytics and you should see click data for your website!**

**OS analytics is a free, open source product designed to give developers the ability to collect and analyze user click data on their website(s). Please create a free account at https://os-analytics.com in order to receive an api key. Then, use our npm package with this api key. See our GitHub Repo for detailed instructions. Have fun collecting data!**