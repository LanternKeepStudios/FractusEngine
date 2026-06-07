AM_CPPFLAGS = -g -std=c++17 -Wall -Wextra -fPIC \
              -I. \
              -I$(FRACTUS_GLEW_INCLUDES) \
              -I$(FRACTUS_GLFW_INCLUDES) \
              -I$(FRACTUS_GLM_INCLUDES)  \
              -I$(FRACTUS_ASSIMP_INCLUDES)

libFractus_la_LIBADD = \
    $(FRACTUS_GLEW_LIBS) \
    $(FRACTUS_GLFW_LIBS) \
    $(FRACTUS_ASSIMP_LIBS)

noinst_LTLIBRARIES = libFractus.la

libFractus_ladir = $(includedir)/Fractus

libFractus_la_SOURCES = Core/Engine.cpp                      \
                        Core/GlfwManager.cpp                 \
                        Core/Logger.cpp                      \
                        Input/InputManager.cpp               \
                        Rendering/CubemapTexture.cpp         \
                        Rendering/GpuMesh.cpp                \
                        Rendering/Material.cpp               \
                        Rendering/Mesh.cpp                   \
                        Rendering/Model.cpp                  \
                        Rendering/Renderer.cpp               \
                        Rendering/Shader.cpp                 \
                        Rendering/SkyBox.cpp                 \
                        Rendering/Texture2D.cpp              \
                        ResourceManagement/AssetImporter.cpp \
                        Scene/LightNode.cpp                  \
                        Scene/ModelNode.cpp                  \
                        Scene/Scene.cpp                      \
                        Scene/SceneNode.cpp                  \
                        Window/Window.cpp                    \
                        Window/WindowState.cpp               \
                        ThirdParty/stb_image.cpp              \
                        CameraNode.cpp
