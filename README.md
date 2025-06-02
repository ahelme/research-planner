# 📊 Research Planner

**Single-page HTML & Javascript research project management tool with advanced security features**

A self-contained, single-file web application for planning and tracking academic research projects, dissertations, and thesis work. Built with security-first architecture and optimized for both digital use and professional printing.

![Version](https://img.shields.io/badge/version-1.4.0-blue)
![Security](https://img.shields.io/badge/security-enterprise%20grade-green)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

## User Interface

![Research-Planner 1 4 0](https://github.com/user-attachments/assets/5f7f663a-c459-49de-af3f-70148861d24d)


## ✨ Key Features

### 📋 **Research or Project Planning**
- **Hierarchical Structure**: Activities contain multiple elements with detailed tracking
- **Automatic Date Calculation**: Cascading date progression from your research start date (set your own with calendar date picker)
- **Drag & Drop Reordering**: Intuitive activity and element reorganization
- **Progress Tracking**: Editable progress indicators to completion 100%
- **Date Sent** Auto color-coded field to mark date chapter / docs sent to Supervisor / Committee etc.
- **Feedback Requested Date** Auto color-coded field to mark date feedback requested on chapter / docs
- **Supervision / Meetings Date**: Auto color-coded field to clearly mark out meetings with supervisors, committee, collaborators etc.

### 💾 **Data I/O and Offline Functionality**
- **Secure Export/Import**: JSON format with security metadata
- **Clipboard Integration**: One-click copy to clipboard for easy saving
- **Data Persistence**: Automatic date recalculation on data load
- **Version Tracking**: Built-in version control for exported files
- **Backup-Friendly**: Self-contained files that work anywhere
- **Work Offline**: Once app is downloaded, no internet connection is required as app runs locally on your file-system

### 💾 **Pre-Built 3-Year Doctoral Research Template**
- **PhD Template**: 3-Year template loaded by default - interviews/creative research based project
- **Editable Template**: Drag, drop, extend, customise, reorganise, edit, delete, make it yours
- **Delete All**: Use Delete All button to delete template and create your own 

### 🖨️ **Print Optimization**
- **Professional Layout**: Optimized for landscape printing and PDF export
- **Print-Specific Styling**: Clean, ink-efficient design for hard copies
- **View Mode**: Read-only presentation mode ideal for printing
- **Automatic Scaling**: 65% zoom optimization for better page fitting
- **Smart Element Hiding**: Print mode removes interactive elements automatically

### 🛡️ **Enterprise Security**
- **Content Security Policy**: Browser-level protection against script injection
- **Real-time Input Sanitization**: Live protection as you type
- **File Upload Security**: Multi-layer validation and threat scanning
- **Visual Security Feedback**: Immediate alerts when threats are blocked
- **Debug Console**: Real-time security monitoring and event logging
- **Host App Securely**: Host app on your university web-server to make it available for your researchers

## 🚀 Quick Start

### **Instant Setup**
1. Download the `index.html` file or click Download App and save .html file to desktop
2. Open .html file in any modern web browser
3. Start planning your research immediately
4. No installation, no dependencies, no servers required

### **Basic Usage**
1. **Use Template or Delete All**: Use existing template as the basis for your own project or Delete All to start fresh
2. **Set Research Start Date**: Use the date picker to set when your research begins
3. **Add Activities**: Use the blue `+` button to create major research phases
4. **Add Elements**: Use green `+ Element` buttons to break activities into tasks
5. **Edit Content**: Click any cell to edit (days, notes, progress, etc.)
6. **Track Progress**: Use the colored supervisor columns for communication tracking
7. **Save Your Work!**: Use `💾 Save Data` to export your plan (recommended: save regularly)
8. **Print Research Plan**: Click View Mode button then navigate to browser menu > File > Print or Export to PDF then print in Landscape Orientation (for best layout: use Chrome)

## 📖 Detailed Features

### **Activity & Element Management**
- **Activities**: Major research phases (e.g., "Literature Review", "Data Collection")
- **Elements**: Specific tasks within activities (e.g., "Draft Chapter", "Conduct Interviews")
- **Automatic Numbering**: Elements are automatically numbered within each activity
- **Time Calculation**: Automatic weeks calculation from days input
- **Date Cascading**: Subsequent items automatically start when previous items end

### **Supervisor Collaboration Tracking**
Three color-coded columns for academic supervision:
- **🔵 Supervision/Meeting** (Light Blue): Record meeting dates and outcomes
- **🟡 Docs Sent** (Yellow): Track when documents are sent to supervisors  
- **🟢 Feedback Requested** (Green): Monitor feedback requests to communicate clearly with your committee

### **Modes & Views**
- **Edit Mode**: Full functionality with drag-and-drop, editing, and controls
- **View Mode**: Read-only presentation mode, optimized for printing and sharing
- **Print Mode**: Automatic activation during printing with optimized layout (choose View Mode first)

### **Data Export/Import**
```json
{
  "version": "1.4.0",
  "appName": "Research Planner - Enterprise Security Edition",
  "exportDate": "2025-01-15T10:30:00.000Z",
  "researchStartDate": "2025-03-01",
  "totalActivities": 12,
  "totalElements": 48,
  "data": [...],
  "securityInfo": {
    "cspEnabled": true,
    "sanitizationVersion": "enhanced"
  }
}
```

## 🛡️ Security Features

### **Multi-Layer Protection**
- **Content Security Policy**: Prevents script injection attacks
- **Input Sanitization**: Real-time protection against XSS and injection
- **File Validation**: Comprehensive upload security scanning
- **Schema Validation**: Ensures data integrity and structure
- **Threat Detection**: Monitors for 12+ types of malicious patterns

### **Visual Security Indicators**
- **Green Status**: `🛡️ App Status: Secure 🛡️` when all protections active
- **Yellow Flash**: Indicates when dangerous content is detected and removed
- **Security Warnings**: Pop-up alerts for threat detection
- **Debug Console**: Detailed security event logging available

### **Enterprise-Ready**
- Self-contained architecture eliminates server-side vulnerabilities
- Client-side-only operation for maximum data privacy
- No external dependencies or API calls
- Suitable for sensitive research data handling

## 💻 Technical Specifications

### **Browser Compatibility**
- **Chrome/Edge**: Full support (recommended)
- **Firefox**: Full support  
- **Safari**: Full support
- **Mobile**: Responsive design, works on tablets (phone likely too small)

### **File Specifications**
- **Input**: JSON files up to 10MB
- **Output**: Standards-compliant JSON with metadata
- **Format**: Self-documenting with version control
- **Security**: All exports include security validation metadata

### **Performance**
- **Startup**: Instant loading (< 1 second)
- **Rendering**: Real-time table updates
- **Security**: < 5ms overhead per input
- **Memory**: Efficient handling of large research plans (1000+ activities)

## 📊 Use Cases

### **Academic Research**
- **PhD Dissertations**: Multi-year project planning and tracking
- **Master's Thesis**: Semester and year-long research organization  
- **Research Proposals**: Grant application timeline development
- **Academic Papers**: Manuscript development and submission tracking

### **Professional Applications**
- **Consulting Projects**: Client deliverable timeline management
- **Report Writing**: Complex document development tracking
- **Training Programs**: Curriculum development and delivery planning
- **Compliance Projects**: Regulatory milestone and deadline management

## 🎯 Advanced Tips

### **Efficient Planning**
1. **Start Broad**: Begin with major activities, then break into elements
2. **Be Realistic**: Use actual working days, not calendar days
3. **Buffer Time**: Add extra days for revisions and unexpected delays
4. **Regular Updates**: Update progress and adjust timelines as needed

### **Supervisor Management**
1. **Color Coding**: Use the three supervisor columns consistently
2. **Date Tracking**: Record actual dates when documents are sent/received
3. **Deadline Monitoring**: Use "Feedback Requested" for deadline tracking
4. **Meeting Notes**: Brief meeting outcomes in the supervision column

### **Print Optimization**
1. **Use View Mode**: Switch to View Mode before printing
2. **Landscape Orientation**: Select landscape in your browser's print dialog
3. **PDF Export**: Print to PDF for sharing and archiving
4. **Scale Adjustment**: Browser automatically optimizes scaling for best fit

## 🔧 Troubleshooting

### **Common Issues**

**Q: The security indicator shows yellow/warning**  
A: Some security features may not be fully active. Check that you're using a modern browser and the file wasn't modified.

**Q: Dates aren't calculating correctly**  
A: Ensure your Research Start Date is set correctly. All dates cascade from this baseline.

**Q: Print layout looks wrong**  
A: Make sure you're in View Mode and using landscape orientation in your print settings.

**Q: Can't import my JSON file**  
A: Verify the file is valid JSON and under 10MB. Check the debug console for specific error messages.

### **Debug Console**
Access detailed diagnostics via the `📊 Console` button:
- Security event monitoring
- Data validation status
- Performance metrics
- Error debugging information

## 🤝 Contributing and Future Development Roadmap

We welcome contributions! Areas for enhancement:

- **Themes**: Alternative color schemes, layouts and dark/light mode
- **Templates**: Pre-built research plan templates
  - Export your .json file and either make a Pull Request on Github or just send it to us here https://annahelme.com/contact/ 
- **Editable Column Headers**: To more easily use for multiple project-management purposes
- **Export Formats**: Additional export options (CSV, Excel)
- **Integrations**: Calendar and project management tool connections

## 📄 License

MIT License - Feel free to use, fork, modify, and distribute for any purpose.

## 👥 Authors

- **Primary Developer**: Anna Helme
- **AI Collaboration**: Claude Sonnet
- **Security Architecture**: Joint development
- **Feature Design**: Collaborative iteration

## 🔗 Links

- **Security Documentation**: See [SECURITY.md](SECURITY.md) for detailed security information
- **Issue Reporting**: Use GitHub Issues for bug reports and feature requests
- **Latest Release**: Download the most recent version from releases

## 🌟 Acknowledgments

Built with enterprise-grade security principles, user-centered design, and academic workflow expertise. Special thanks to the research community for inspiration and feedback.

---

**Ready to transform your research planning?** Download the HTML file and start organizing your academic journey today! 🎓
