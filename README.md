{
    "manifest_version": 3,
    "name": "",
    "description": "",
    "version": "1.0",
    "content_scripts": [
    {
        "js": ["scripts/"],
        "matches": ["http://*/*", "https://*/*"]
    }
    ],
    "background": {
        "service_worker": "/",
        "type": "module"
    },
    "permissions": ["activeTab", "storage"],
    "action": {
      "default_popup": "",
      "default_icon": "a"
    }
}
