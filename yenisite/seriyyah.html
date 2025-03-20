import { useState } from 'react';
import { Card, CardContent } from "@/components/ui/card";
import { Input } from "@/components/ui/input";
import { Button } from "@/components/ui/button";
import { Lock, User, Home, Shield, Code } from 'lucide-react';
import { motion } from "framer-motion";
import { BrowserRouter as Router, Route, Routes, Link } from "react-router-dom";

function LoginPage() {
  const [email, setEmail] = useState("");
  const [password, setPassword] = useState("");

  const handleLogin = () => {
    console.log("Logging in with", email, password);
  };

  return (
    <div className="flex h-screen items-center justify-center bg-gradient-to-r from-blue-900 to-black text-white">
      <motion.div 
        initial={{ opacity: 0, scale: 0.8 }}
        animate={{ opacity: 1, scale: 1 }}
        transition={{ duration: 0.5 }}
      >
        <Card className="w-96 p-6 bg-blue-950 shadow-2xl rounded-2xl border border-blue-600">
          <CardContent>
            <h1 className="text-3xl font-bold text-center mb-6 text-blue-400">Seriyyah Cyber</h1>
            <div className="space-y-4">
              <div className="flex items-center border-b border-blue-700 py-2">
                <User className="text-blue-400 mr-3" />
                <Input 
                  type="email" 
                  placeholder="Email" 
                  value={email} 
                  onChange={(e) => setEmail(e.target.value)} 
                  className="bg-transparent border-none focus:ring-0 text-white"
                />
              </div>
              <div className="flex items-center border-b border-blue-700 py-2">
                <Lock className="text-blue-400 mr-3" />
                <Input 
                  type="password" 
                  placeholder="Password" 
                  value={password} 
                  onChange={(e) => setPassword(e.target.value)} 
                  className="bg-transparent border-none focus:ring-0 text-white"
                />
              </div>
              <Link to="/dashboard">
                <Button onClick={handleLogin} className="w-full bg-blue-600 hover:bg-blue-500 transition rounded-xl py-2 text-lg">
                  Login
                </Button>
              </Link>
            </div>
          </CardContent>
        </Card>
      </motion.div>
    </div>
  );
}

function Dashboard() {
  return (
    <div className="h-screen bg-gradient-to-r from-blue-900 to-black text-white p-6">
      <h1 className="text-4xl font-bold text-center text-blue-400 mb-8">Welcome to Seriyyah Cyber</h1>
      <nav className="flex justify-center space-x-6 text-lg">
        <Link to="/" className="flex items-center space-x-2 text-blue-300 hover:text-blue-500 transition">
          <Home /> <span>Home</span>
        </Link>
        <Link to="/security" className="flex items-center space-x-2 text-blue-300 hover:text-blue-500 transition">
          <Shield /> <span>Security</span>
        </Link>
        <Link to="/development" className="flex items-center space-x-2 text-blue-300 hover:text-blue-500 transition">
          <Code /> <span>Development</span>
        </Link>
      </nav>
    </div>
  );
}

export default function App() {
  return (
    <Router>
      <Routes>
        <Route path="/" element={<LoginPage />} />
        <Route path="/dashboard" element={<Dashboard />} />
      </Routes>
    </Router>
  );
}
