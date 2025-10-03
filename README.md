# 🎬 MovieFinder

A modern React application that helps users discover and search through thousands of movies using TMDB API, with trending movies tracking powered by Appwrite.

![Hero Banner](/public/hero.png)

## ✨ Features

- **🔍 Real-time Search**: Instantly search through thousands of movies
- **📈 Trending Movies**: Track and display most searched movies
- **🎯 Detailed Movie Cards**: View essential movie information including:
  - Title
  - Rating
  - Release Year
  - Original Language
  - Movie Poster
- **💫 Modern UI**: Clean and responsive design with smooth animations
- **⚡ Performance**: Optimized with debounced search for better performance

## 🛠️ Built With

- **Frontend**: React + Vite
- **Styling**: TailwindCSS
- **Backend**: Appwrite
- **API**: TMDB (The Movie Database)
- **State Management**: React Hooks
- **Performance**: React-Use (Debounce)

## 🚀 Getting Started

1. **Clone the repository**
```bash
git clone https://github.com/MehmetKaplan33/react-movie-app
cd movie-project
```

2. **Install dependencies**
```bash
npm install
```

3. **Set up environment variables**
Create a `.env.local` file based on `.env.example`:
```env
VITE_TMDB_API_KEY=your_tmdb_api_key
VITE_APPWRITE_PROJECT_ID=your_appwrite_project_id
VITE_APPWRITE_DATABASE_ID=your_appwrite_database_id
VITE_APPWRITE_COLLECTION_ID=your_appwrite_collection_id
```

4. **Run the development server**
```bash
npm run dev
```

## 📱 Features Preview

### Search Movies
- Real-time search with debouncing
- Dynamic results update
- Loading states with spinner

### Movie Display
- Grid layout for movie cards
- Responsive design for all screen sizes
- Fallback image for missing posters

### Trending Section
- Top 5 most searched movies
- Automatic updates based on user searches
- Horizontal scrollable list

## 🔧 Configuration

The project uses several key configurations:

- **Vite**: Modern build tool for faster development
- **ESLint**: Code quality and consistency
- **TailwindCSS**: Utility-first CSS framework
- **Appwrite**: Backend as a Service for trending movies

## 📝 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 💬 Contact

Mehmet Kaplan

- GitHub: [@Kaplan_Mehmet_33]([https://github.com/mehmetkaplan](https://github.com/MehmetKaplan33))
- LinkedIn: [Mehmet Kaplan](https://www.linkedin.com/in/mehmet-kaplan-601013294/)

Proje Linki: [https://github.com/MehmetKaplan33/React-Movie-App](https://github.com/MehmetKaplan33/React-Movie-App)
