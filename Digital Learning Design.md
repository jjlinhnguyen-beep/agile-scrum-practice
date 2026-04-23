# 🏗️ Dự án Thiết kế Khóa học Online

### 📊 Cấu trúc quản lý dự án

```mermaid
graph TD
    Project[Online Course Project] --> GitHub[GitHub: Project Management]
    Project --> Cloud[Google Drive: Media Assets]
    
    subgraph GitHub
        A[README.md: Learning Path & Vision]
        B[Issues: Task Tracking]
        C[ASSETS.md: Links to Video/PDF]
    end
    
    subgraph Cloud
        D[Video Lectures]
        E[3D Models/Visuals]
        F[Reading Materials]
    end
    
    A --> D
    B --> E
