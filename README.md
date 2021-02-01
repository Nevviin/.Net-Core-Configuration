# .Net-Core-Configuration
.Net Core Configuration And Configuration Providers



# Configuration as dictionary and fetching keys based on values
   var configDictionary = _configuration.AsEnumerable().ToDictionary(p => p.Key, x => x.Value);
   
   var targetKey = configList.FirstOrDefault(v => v.Value =="searchString").Key;
