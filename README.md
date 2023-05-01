# PIVA-detection---Nuclei-template
A straightforward template that can be used in such a way as to detect whether a website has an Italian VAT or not. It's definitely not a vulnerability, however, it might provide further information for GDPR compliance.

### Configuration guide

Once cloned, move the .yaml file to the nuclei templates folder:

```
mv /path/to/file/piva-detection.yaml ~/nuclei-templates
```
After that, move to the nuclei-templates folder, then the new template can easily be tested by executing:

```
nuclei -t piva-detection.yaml -u https://example.com
```


