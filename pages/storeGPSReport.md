# storeGPSReport

## 機能

## 発火コード

```typescript
const storeGPSReportApp = express();
storeGPSReportApp.use(bodyParser.urlencoded({extended: false}));
storeGPSReportApp.use(bodyParser.json());
storeGPSReportApp.use(cors({origin: true}));
storeGPSReportApp.post('/', storeGPSReportFunction.storeGPSReport);
export const storeGPSReport = functions.https.onRequest(storeGPSReportApp);
```
